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
    return "Node.js backend engineer who speaks fluent microservices, event-driven architecture. I make systems reliable, fast, and slightly over-engineered on purpose.";
  }

  contact() {
    return {
      email: "pranavs.engineer@gmail.com",
      altEmail: "connectpranavs@gmail.com",
      github: "github.com/prnv404",
      linkedin: "linkedin.com/in/pranav-s-2263a9352",
      telegram: "t.me/prnv404"
    };
  }

  journey() {
    return [
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
      name: "DUCK - A question practice app for competetive exams",
      stack: ["NestJS", "GraphQL", "Drizzle ORM", "Rag", "ReactNative Expo", "Supabase"],
      vibe: "Like Doulingo, but for indian competetive exams"
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

  hireMe() {
    console.log("%c Pranav S is online ", "color:#00ff88; background:#0d1117; font-size:18px; padding:12px 24px; border-radius:12px; font-weight:bold;");
    console.log("%c Available for backend roles • freelance • contract • coffee chats ", "color:#8b949e; font-size:14px; padding:4px 0;");
    console.log("%c Shoot a mail → pranavs.engineer@gmail.com ", "color:#58a6ff; font-size:14px;");
    return "Thanks for stopping by! Now go make something awesome";
   }
}


