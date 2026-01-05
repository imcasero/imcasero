```bash
$ cat diego.ts
```
```typescript
const diego = {
  role: "Frontend Developer",
  company: "CaixaBank Tech",
  location: "Madrid, Spain",
  experience: {
    years: "2+",
    impact: {
      current: "2K+ daily users on React apps",
      previous: "30% bug reduction through testing strategy"
    }
  },
  
  stack: {
    frontend: {
      core: ["React 18", "TypeScript 5.x", "Next.js 15", "Astro"],
      architecture: ["Microfrontends", "Component-driven design"],
      styling: ["Tailwind", "CSS Modules", "SASS"],
      testing: ["Jest", "Vitest", "React Testing Library"]
    },
    backend: {
      runtime: ["Node.js", "NestJS"],
      databases: ["PostgreSQL", "MySQL"],
      orm: ["Prisma"]
    },
    tools: ["Git", "Docker", "CI/CD"]
  },

  currentProject: {
    name: "ChefFlow",
    problem: "Recipe apps give you '200g flour' + '1 cup flour' as separate items",
    solution: "Smart ingredient aggregation with unit normalization",
    repo: "github.com/Chefflow"
  },

  learning: {
    exploring: ["Rust", "Go", "Python"]
  },

  openTo: {
    remote: "Europe",
    relocation: {
      location: "Geneva, Switzerland",
      availability: "Immediate"
    }
  },

  contact: {
    portfolio: "imcasero.dev",
    linkedin: "linkedin.com/in/imcasero",
    email: "diegocaserosmr@gmail.com"
  }
};

export default diego;
```
