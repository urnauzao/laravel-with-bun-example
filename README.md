# Doc Oficial:
[https://bun.sh](https://bun.sh)
# Vídeo
[https://youtu.be/AM0TgbSQJGc](https://youtu.be/AM0TgbSQJGc)

# Remover NPM
git rm package-lock.json 
git commit -m "Remove package-lock.json" package-lock.json

# Remover PNPM
git rm pnpm-lock.yaml 
git commit -m "Remove pnpm-lock.yaml" pnpm-lock.yaml

# Remover Yarn
git rm yarn.lock
git commit -m "Remove yarn.lock" yarn.lock

# Comando que remove
rm -rf package-lock.json pnpm-lock.yaml yarn.lock


# Bun e Bunx
Em resumo, o `bun` é usado para gerenciar pacotes e dependências em projetos JavaScript, enquanto o `bunx` é usado para executar comandos de pacotes de forma conveniente e temporária

# Opções de instalação:
- macOS/Linux (curl)
- NPM
- Homebrew
- Docker
- Proto

# Instalar o bun via sail:
> sail bun install

# Executar ambiente de Dev
> sail bun run dev

# Realizar Build para Produção
> sail bun run build


