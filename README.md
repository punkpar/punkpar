Hi, I'm Ben.

I believe in taking back control. Of our infrastructure. Of our data. Of our relationship with the technology we use every day.

Every closed platform is a leash. Every proprietary API is a landlord. I build things locally, own my data, and keep my infrastructure on hardware I can touch. That's the homelab ethos, and it's how I think about almost everything I do.

I run llama.cpp with TurboQuant+ on consumer GPUs because the best AI is the one you control. Not the one you rent from a company that reads your conversations, sets the rules, and can change the terms whenever they like. I don't need a 100B parameter model to be useful. I need models I can run, audit, and understand. Local AI isn't a downgrade. It's the upgrade.

I'm against generative AI for art and culture. Art is human. Music is human. Creativity isn't a prompt. It's a lived experience, and no amount of training data replaces the weird, specific, irreplaceable thing that happens when a real person makes something. I won't use AI to replace artists, musicians, or creators, and I think the people building tools that do are selling a counterfeit version of creativity. That's not progress, it's theft with better marketing.

But I do believe in AI as a tool. A homelab dashboard that alerts you before your backups fail. A voice assistant that controls your lights without phoning home to some corporation's cloud. A model that helps you understand a codebase without sending your code to someone else's server. That's AI worth building. The goal isn't to automate humanity out of the loop. It's to give people tools that amplify what they already do well.

What I build:

- **llama.cpp TurboQuant+** is my main project. A fork of llama.cpp with TurboQuant+ KV cache quantization, 328 upstream commits merged, running on consumer RTX 4070 and RTX 3050 hardware. No API keys. No subscriptions. No telemetry. Just local inference on machines I own.
- **Homelab** is the broader infrastructure project. Docker-based media stack, AI inference, automation, backups, all self-hosted, all auditable, all mine.
- **Instructions** is where I keep system prompts and configurations for my local LLMs. Because your AI should know your context, not some corporation's.

My philosophy is simple. The best technology is the kind you own. Not rent. Not subscribe to. Own. Self-hosted when possible. Open source when available. Local by default. Human creativity is irreplaceable. AI should assist, not replace.

A homelab is the best classroom I've ever had. I didn't learn networking from a textbook. I learned it by watching my SSH tunnels break and figuring out why. I didn't learn Docker from a bootcamp. I learned it by staring at a busted compose file until the health checks turned green. Every broken backup script, every failed VPN connection, every time a container mysteriously died at 3am taught me something a course never could. The skills you build when you're the one who has to fix the system at midnight stay with you. They're not theoretical, and they don't expire. If you want to learn how computers actually work, build one of these. Break things. Fix them. Read the logs. Read them again. You'll come out the other side knowing more than any certificate can give you.

My lab runs across a few machines. ryzen7600 is the AI inference host with an RTX 4070. servarr is the media and Docker workhorse. n100 is the always-on backbone running the MCP gateway. proxmox handles virtualization. m75q is my workstation. They're all consumer hardware, all running open source, all mine.

If you want to build this stuff too, you can. That's the whole point.
