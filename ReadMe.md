# Hi, I'm Pranav 👋
Node.js Backend Engineer | Microservices | Event-Driven | Docker + AWS

```js

class Pranav {
  constructor() {
    this.name = "Pranav S";
    this.from = "Kochi, Kerala, India";
    this.alias = ["prnv404", "pranavs", "the RabbitMQ evangelist"];
    this.currentMood = "Building things that scale and don't wake me up at 3AM";
  }

  about() {
    return "Node.js backend engineer who turned a bus ticketing idea into reality, survived legacy Node versions, and now speaks fluent microservices, event-driven architecture, and Docker. I make systems reliable, fast, and slightly over-engineered — on purpose.";
  }

  contact() {
    return {
      email: "pranavs.engineer@gmail.com",
      altEmail: "connectpranavs@gmail.com",
      phone: "+91 9567296056",
      github: "github.com/prnv404",
      linkedin: "linkedin.com/in/pranav-s-2263a9352",
      telegram: "t.me/prnv404"
    };
  }

  journey() {
    return [
      {
        role: "Product Developer",
        company: "BUS3",
        period: "Apr 2025 – Aug 2025",
        story: "Built a real-time bus ticketing + live tracking system with NFC cards, Kafka, MQTT, Kubernetes, and a full operator dashboard. Validated with real Kerala bus operators."
      },
      {
        role: "Backend Developer",
        company: "IODatalabs (GoCXM)",
        period: "Mar 2024 – Apr 2025",
        story: "Shipped production microservices using Node.js, PostgreSQL, Docker, AWS Fargate, RBAC, CloudWatch — all while drinking too much chai."
      },
      {
        role: "Freelance Backend Engineer",
        period: "2023 – 2024",
        story: "Stayhopper (hospitality), payment gateway migrations on ancient Node.js, in-house LeetCode tracker with Docker + CI/CD"
      },
      {
        role: "Node.js Volunteer",
        company: "Kerala Police Cyberdome (BSafe)",
        period: "Dec 2022 – Apr 2023",
        story: "My first real-world contribution: migrated MongoDB → Elasticsearch, fixed bugs under mentorship, worked directly with law enforcement devs"
      }
    ];
  }

  currentlyBuilding() {
    return {
      name: "Webhook Platform as a Service",
      stack: ["NestJS", "GraphQL", "Drizzle ORM", "RabbitMQ", "Next.js", "AWS Fargate"],
      vibe: "Like Svix, but with more retries and prettier dashboards"
    };
  }

  npmEgo() {
    return [
      "fastnet"     // Express-inspired minimal web framework
      "netx-tunnel" // Secure localhost → public URL tunnel (with custom .d.ts heroics)
      "safex-store" // Encrypted CLI secret manager (Bun.js powered)
    ];
  }

  skills() {
    return {
      languages: ["TypeScript", "JavaScript", "Java", "Bash", "SQL"],
      runtimes: ["Node.js", "Bun.js"],
      frameworks: ["NestJS", "Express", "Fastify", "Koa", "Next.js"],
      databases: ["PostgreSQL", "MongoDB", "Redis", "Elasticsearch", "OpenSearch", "MySQL", "LowDB"],
      messageQueues: ["RabbitMQ", "Kafka", "BullMQ", "Redis Streams", "Qstash"],
      infra: ["Docker", "Kubernetes", "Helm", "AWS (ECS, Fargate, Lambda, S3, CloudWatch, X-Ray)", "DigitalOcean"],
      protocols: ["HTTP/3", "WebSocket", "gRPC", "MQTT", "GraphQL", "REST"],
      tools: ["Prisma", "Drizzle", "TypeORM", "Jest", "Supertest", "GitHub Actions", "Nx", "Grafana", "Prometheus", "Loki"],
      paymentGateways: ["Stripe", "Razorpay", "Cashfree", "MamoPay", "Telr"],
      designPatterns: ["I use Dependency Injection so much even my coffee depends on it"]
    };
  }

  funFacts() {
    return [
      "Once ran production Node.js v8 in 2024 just to migrate a payment gateway",
      "Has written TypeScript definitions for a library that didn't have any",
      "Believes every service deserves a retry queue and a health check",
      "Thinks 404 pages are an art form",
      "Currently learning Go… slowly"
    ];
  }

  ping() {
    console.log("%c Hey there! You found me ", "background:#1a1a1a;color:#00ff88;padding:10px;border-radius:8px;font-size:16px;");
    return "Open to interesting backend gigs, system design chats, or just saying hi → pranavs.engineer@gmail.com";
  }
}

// Export so people can play with it in devtools
export default new Pranav();

// Try in console:
// (new Pranav()).ping()
