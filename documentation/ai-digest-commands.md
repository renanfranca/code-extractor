# AI Digest commands

# Generate AI Digest

## Generate AI Digest for jhipster-lite

### Fontend

```bash
cp /home/renanfranca/projects/code-extractor/src/main/resources/aidigest/.aidigestignore-jhlite-frontend /home/renanfranca/projects/jhipster-lite/target/.aidigestignore-jhlite-frontend
npx ai-digest -i /home/renanfranca/projects/jhipster-lite -o /home/renanfranca/projects/code-extractor/target/aidigest/jhlite-frontend/codebase.md --ignore-file target/.aidigestignore-jhlite-frontend --show-output-files --whitespace-removal
```

### Backend

```bash
npx ai-digest -i /home/renanfranca/projects/jhipster-lite --ignore-file /home/renanfranca/projects/code-extractor/src/main/resources/aidigest/.aidigestignore-jhlite-backend --show-output-files
```

# Prompts to generate custom AI Instructions

## With Claude

### jhipster-lite frontend

Can you write me a good custom instructions prompt for development of this Vue, Typescript application?
Always write all the source files out in full and use Claude Artifacts.

## With ChatGPT

### jhipster-lite frontend

Can you write me a good custom instructions prompt for development of this Vue, Typescript application?
Always write all the source files out in full and use ChatGPT file search tools instead of code interpreter tools.
