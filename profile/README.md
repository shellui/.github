<div align="center">

**Build the app. Not the infrastructure.**

Shellui is the opinionated microfrontend shell for modern web apps.<br>
Navigation, settings, sign-in, files, hosting and email come built in, so you ship the part only you can build.

[Website](https://shellui.com) · [Docs](https://docs.shellui.com) · [Playground](https://playground.shellui.com) · [For AI agents](https://shellui.ai)

</div>

### Get started

```bash
npm install -g @shellui/cli
shellui init react
shellui start
```

Working with a coding agent? Tell it `fetch https://shellui.ai`, or install the skill with `npx skills add shellui/skills --skill shellui`.

### Repositories

**Shell and SDK**
- [shellui](https://github.com/shellui/shellui): the shell, the CLI and the SDK
- [playground](https://github.com/shellui/playground): a live demo, and the shortest working example

**Apps inside the shell**
- [admin](https://github.com/shellui/admin): users, sign-in, webhooks and service settings
- [files](https://github.com/shellui/files): the file explorer and file picker

**Services**, one set per region
- [identity-service](https://github.com/shellui/identity-service): sign-in, companies and tokens
- [storage-service](https://github.com/shellui/storage-service): file storage with a Supabase-compatible API
- [hosting-service](https://github.com/shellui/hosting-service): deploys and serves Shellui apps
- [email-service](https://github.com/shellui/email-service): templates and sends email

**For AI agents**
- [skills](https://github.com/shellui/skills): Agent Skills for Shellui
- [ai](https://github.com/shellui/ai): the source of shellui.ai

**Brand**
- [website](https://github.com/shellui/website): shellui.com and the [Shellui guidelines](https://shellui.com/guidelines/)

### Contribute

Issues and pull requests are welcome on every repository. Each README has a Get started section, and coding agents start with the `AGENTS.md` file at the root.
