### How to bootstrap:
 - curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
 - npm init svelte my-app || pnpm create svelte my-app
 - cd my-app
 - pnpm install
 - git init && git add -A && git commit -m "Initial commit"
 - pnpx playwright install && sudo pnpx playwright install-deps && pnpm run test
 - pnpm run dev -- --open
