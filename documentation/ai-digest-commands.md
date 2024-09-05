# AI Digest commands

# Generate AI Digest

## Generate AI Digest for jhipster-lite

### Fontend

```bash
cp /home/renanfranca/projects/code-extractor/src/main/resources/aidigest/.aidigestignore-jhlite-frontend /home/renanfranca/projects/jhipster-lite/target/.aidigestignore-jhlite-frontend
npx ai-digest -i /home/renanfranca/projects/jhipster-lite -o /home/renanfranca/projects/code-extractor/target/aidigest/jhlite-frontend/codebase.md --ignore-file target/.aidigestignore-jhlite-frontend --show-output-files
cp /home/renanfranca/projects/code-extractor/target/aidigest/jhlite-frontend/codebase.md /home/renanfranca/projects/code-extractor/target/aidigest/jhlite-frontend/codebase.txt
```

### Backend

```bash
cp /home/renanfranca/projects/code-extractor/src/main/resources/aidigest/.aidigestignore-jhlite-backend /home/renanfranca/projects/jhipster-lite/target/.aidigestignore-jhlite-backend
npx ai-digest -i /home/renanfranca/projects/jhipster-lite -o /home/renanfranca/projects/code-extractor/target/aidigest/jhlite-backend/codebase-jhlite-backend.md --ignore-file target/.aidigestignore-jhlite-backend --show-output-files --whitespace-removal
cp /home/renanfranca/projects/code-extractor/target/aidigest/jhlite-backend/codebase-jhlite-backend.md /home/renanfranca/projects/code-extractor/target/aidigest/jhlite-backend/codebase-jhlite-backend.txt
```

## Generate AI Digest for renanfranca.github.io

```bash
cp /home/renanfranca/projects/code-extractor/src/main/resources/aidigest/.aidigestignore-renanfranca-github-io /home/renanfranca/projects/renanfranca.github.io/.aidigestignore-renanfranca-github-io
npx ai-digest -i /home/renanfranca/projects/renanfranca.github.io -o /home/renanfranca/projects/code-extractor/target/aidigest/renanfranca-github-io/blog-posts.md --ignore-file .aidigestignore-renanfranca-github-io --show-output-files
rm -rf /home/renanfranca/projects/renanfranca.github.io/.aidigestignore-renanfranca-github-io
cp /home/renanfranca/projects/code-extractor/target/aidigest/renanfranca-github-io/blog-posts.md /home/renanfranca/projects/code-extractor/target/aidigest/renanfranca-github-io/blog-posts.txt
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

### renanfranca.github.io

Start from here you always read this blog-posts.txt file before answer.
And you will write like I write and try the best to use the words I used.
if you find some grammar mistakes feel free to correct it. Do you understand?
