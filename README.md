# How to Debug Kubernetes Pods with Traceloop

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DevFest](https://img.shields.io/badge/DevFest-Lagos%202025-blue)](https://devfest.withgoogle.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-debugging-326CE5?logo=kubernetes)](https://kubernetes.io/)
[![freeCodeCamp](https://img.shields.io/badge/Tutorial-freeCodeCamp-0A0A23?logo=freecodecamp)](https://www.freecodecamp.org/news/how-to-debug-kubernetes-pods-with-traceloop-a-complete-beginners-guide/)

> **CCTV for your Kubernetes pods** - See exactly what your applications are doing at the kernel level using eBPF and Traceloop.

Materials and code from my **DevFest Lagos 2025** talk.

## 📖 Full Tutorial

**Want to learn about Traceloop step-by-step?** 

👉 **[Read the complete tutorial on freeCodeCamp](https://www.freecodecamp.org/news/how-to-debug-kubernetes-pods-with-traceloop-a-complete-beginners-guide/)**

The freeCodeCamp article covers:
- ✅ Why traditional Kubernetes debugging falls short
- ✅ How eBPF and Traceloop work under the hood
- ✅ Complete installation guide
- ✅ Real crash debugging walkthrough
- ✅ Production use cases and best practices

---

## 🎯 What's in This Repository

This repo contains the **code, slides, and hands-on examples** from my DevFest talk.

### 📊 `/slides` - Presentation Materials
- Full slide deck (Link)
- Code screenshots

### 💻 `/demo` - Hands-On Tutorial
- Crash app that fails with generic errors
- Setup scripts for quick start
- Complete kubectl commands
- Expected output examples

### 📚 `/docs` - Quick Reference
- Installation cheat sheet
- Troubleshooting guide
- FAQ

### 🔗 `/resources` - Community Links
- Official documentation
- Kubernetes Slack channel
- Related tools

---

## 🚀 Quick Start

Want to try the demo yourself?

### Prerequisites
- Kubernetes cluster (minikube, kind, or cloud)
- kubectl installed
- Cluster admin permissions

### Installation
```bash
# Clone this repo
git clone https://github.com/emidowojo/traceloop-devfest-tutorial.git
cd traceloop-devfest-tutorial

# Run the setup
cd demo
chmod +x setup.sh
./setup.sh
```

**For detailed installation steps**, see the [freeCodeCamp tutorial](https://www.freecodecamp.org/news/how-to-debug-kubernetes-pods-with-traceloop-a-complete-beginners-guide/) or (https://inspektor-gadget.io/docs/latest/gadgets/traceloop).

---

## 🎓 Learning Path

**New to Traceloop?** Follow this path:

1. 📖 **[Read the freeCodeCamp article](https://www.freecodecamp.org/news/how-to-debug-kubernetes-pods-with-traceloop-a-complete-beginners-guide/)** - Complete beginner's guide
2. 📊 **[Check the slides](https://docs.google.com/presentation/d/1aSs7_uCZqItxCU-6giCr6Ca1K4B8BCHhZ6GaIYEl1bg/edit?usp=sharing)** - Visual presentation from DevFest
3. 💻 **[Try the demo](./demo/)** - Hands-on crash debugging
4. 💬 **[Join the Inspektor Gadget community](https://kubernetes.slack.com/archives/CSYL75LF6)** - Get help and share experiences

---

## 🔗 Official Resources

### Documentation
- **Inspektor Gadget**: https://inspektor-gadget.io/docs/latest/
- **Traceloop Docs**: https://inspektor-gadget.io/docs/latest/gadgets/traceloop
- **GitHub**: https://github.com/inspektor-gadget/inspektor-gadget

### eBPF Resources
- **What is eBPF?**: https://ebpf.io/what-is-ebpf/

---

## 💬 Community & Support

### Get Help
- **Kubernetes Slack**: [Join workspace](https://slack.k8s.io) → **#inspektor-gadget** channel
- **GitHub Discussions**: https://github.com/inspektor-gadget/inspektor-gadget/discussions
- **Issues**: https://github.com/inspektor-gadget/inspektor-gadget/issues

### Found This Useful?
- ⭐ **Star this repo**
- 📢 **Share on social media**
- 🐦 **Tweet at me**: [@Emidowojo](https://twitter.com/Emidowojo)
- 💬 **Join #inspektor-gadget on Kubernetes Slack**

---

## 👩‍💻 About the Speaker

**Emidowojo Opaluwa** - Documentation Engineer @ Qore

- 🎓 **CNCF LFX Mentorship Alum** - Contributed to Inspektor Gadget project
- 📝 **Blog**: [TechonDiapers](https://techondiapers.hashnode.dev/) - Beginner-friendly tech content
- 🐦 **Twitter**: [@Emidowojo](https://twitter.com/Emidowojo)
- 💼 **LinkedIn**: [opaluwaemidowojo](https://linkedin.com/in/opaluwaemidowojo)
- ✍️ **freeCodeCamp Author**: [Read my articles](https://www.freecodecamp.org/news/author/Tech-On-Diapers/)

---

## 📝 Related Articles

From my freeCodeCamp publication history:
- 📖 **[How to Debug Kubernetes Pods with Traceloop](https://www.freecodecamp.org/news/how-to-debug-kubernetes-pods-with-traceloop-a-complete-beginners-guide/)** *(This tutorial!)*
- 🔍 More debugging and DevOps articles coming soon!

---

## 🤝 Contributing

Found a typo? Have a suggestion? Contributions welcome!

1. Fork this repository
2. Create a feature branch: `git checkout -b feature/improvement`
3. Commit changes: `git commit -m "docs: improve installation guide"`
4. Push and create a Pull Request

---

## 📄 License

This tutorial is licensed under [MIT License](./LICENSE).

The Inspektor Gadget project has its own license. See their [repository](https://github.com/inspektor-gadget/inspektor-gadget) for details.

---

## 🙏 Acknowledgments

- **Inspektor Gadget team** for building amazing debugging tools
- **CNCF** for the LFX Mentorship program
- **freeCodeCamp** for publishing the full tutorial
- **DevFest Lagos 2025** organizers and attendees
- Everyone who provided feedback and suggestions

---

## 📬 Stay Connected

- 🐦 Follow me on Twitter: [@Emidowojo](https://twitter.com/Emidowojo)
- 📝 Read my blog: [TechonDiapers](https://techondiapers.hashnode.dev/)
- 💼 Connect on LinkedIn: [opaluwaemidowojo](https://linkedin.com/in/opaluwaemidowojo)
- 💬 Chat on Slack: #inspektor-gadget channel

---

**⭐ Star this repo if you found it helpful!**

**DevFest Lagos 2025** | Debugging Kubernetes Pods with Traceloop
