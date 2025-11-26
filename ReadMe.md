# Hi, I'm Pranav 👋
Node.js Backend Engineer | Microservices | Event-Driven | Graphql

```ts

class Pranav {
  name = "Pranav S";
  location = "Kochi, Kerala, India";
  role = "Backend Engineer";
  focus = "Node.js • TypeScript • Scalable Systems";

  stack = [
    "NestJS", "TypeScript", "PostgreSQL", "Graphql", 
    "NextJs", "React", "ReactNative", "Drizzle"
  ] as const;

  currentlyBuilding = "DUCK → Duolingo-style app for Indian competitive exams (NestJS + React Native)";

  experience = [
    "IODatalabs (GoCXM) → Production microservices (2024–2025)",
    "Freelance → Payment gateways, Stayhopper, custom tools",
    "Kerala Police Cyberdome → MongoDB → Elasticsearch migration"
  ] as const;

  openSource = ["fastnet", "netx-tunnel", "safex-store"] as const;

  lookingFor = "Backend roles • Contract • Freelance • Interesting problems";

  contact = {
    email: "pranavs.engineer@gmail.com",
    github: "github.com/prnv404",
    linkedin: "linkedin.com/in/pranav-s-2263a9352",
  };

  vibe = "Ships reliable code. Slightly over-engineers on purpose.";

  hireMe() {
    return `Hey! I'm currently open to work → ${this.contact.email}`;
  }
}

const me = new Pranav();
console.log(me.hireMe());



