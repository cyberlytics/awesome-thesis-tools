[//]: # (Author: Christoph P. Neumann)
[//]: # (Title: Awesome Abschlussarbeit Informatik/KI)
[//]: # (Language: de-DE)
[//]: # (Licence: CC BY 4.0)
[//]: # (Kurztitel: Werkzeuge » Abschlussarbeiten)
[//]: # (Lemma: tools-thesis)

# Awesome Abschlussarbeit (Informatik/KI)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-pink.svg)](https://github.com/chetanraj/awesome-github-badges)
[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue?logo=paypal)](https://www.paypal.com/donate/?hosted_button_id=QTDJ2JA58ZM9L)
[![Support on Ko‑fi](https://img.shields.io/badge/Donate-ko--fi-%23FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/cyberlytics)
[![Buy Me A Coffee!](https://img.shields.io/badge/Donate-buymeacoffee-%23FFDD00?logo=buymeacoffee)](https://www.buymeacoffee.com/cyberpetaneuron)

Dies ist eine Tool-Sammlung. Es gibt von mir die weiteren Schwesterseiten im Kontext Informatik/KI: [Digitaler Ressourcen-Pool](https://github.com/cyberlytics/awesome-basics), [Werkzeuge » Software-Engineering](https://github.com/cyberlytics/awesome-software-engineering-tools) und [Werkzeuge » BDCC/AI](https://github.com/cyberlytics/awesome-bdccai-tools).

Hinweise:

- Die Werkzeuge sind im Zweifelsfall für Studierende und private Nutzung, weniger für Unternehmen oder Freelancer (wegen der Lizenzbedingungen/EULA)
- Entstanden an der [OTH Amberg-Weiden](https://www.oth-aw.de/cpn), welche für ein paar Einträge entsprechend den Kontext bildet.
- Die kostenlosen Werkzeuge sind nicht immer Best-in-Class im Vergleich zu kostenpflichtigen/„(€)“ Alternativen, dennoch bleiben kostenpflichtige Angebote hier meist Out-of-Scope
- Ein Windows-zentrischer Ersteindruck durch die Chocolatey-Referenzen kann leicht täuschen, denn die kostenlosen oder quelloffenen Tools gibt es i.d.R. auch für Linux oder macOS mittels snap/flatpak/brew/etc.
- Empfehlung zu [Chocolatey](https://chocolatey.org/install): **choco feature enable -n useRememberedArgumentsForUpgrades**

**Table of Contents**

<!-- toc -->

- [Literaturrecherche & Wissensaufbau](#literaturrecherche--wissensaufbau)
- [Portable Apps](#portable-apps)
- [Generative KI](#generative-ki)
- [LaTeX & PDF](#latex--pdf)
- [Markdown Publishing](#markdown-publishing)
- [Schreiben](#schreiben)
- [Anti-Prokrastination](#anti-prokrastination)
- [Translations](#translations)
- [Evaluation-Werkzeuge](#evaluation-werkzeuge)
- [Management & Agile Methoden](#management--agile-methoden)
- [Kollaborative Werkzeuge](#kollaborative-werkzeuge)
- [Zeichnen](#zeichnen)
- [Presentations](#presentations)
- [Poster](#poster)
- [Plug-Ins / Add-Ins / Extensions](#plug-ins--add-ins--extensions)
- [Bildmaterialien](#bildmaterialien)
- [Mathe](#mathe)
- [Job-Bewerbungen](#job-bewerbungen)
- [Kostenlose Alternativen](#kostenlose-alternativen)
- [Android Apps](#android-apps)
- [Bonus: 3D-Printing](#bonus-3d-printing)
- [Appendix: More Free Student Stuff](#appendix-more-free-student-stuff)
- [Footer](#footer)

<!-- tocstop -->

## Literaturrecherche & Wissensaufbau

- [Google **Scholar**](https://scholar.google.com) | **[ResearchGate](https://www.researchgate.net/)** | **[Semantic Scholar](https://www.semanticscholar.org)**
	- DE: [**DBLP** Computer Science Bibliography](https://dblp.org/) | [**BASE**: Bielefeld Academic Search Engine](https://www.base-search.net/)
	- Weitere Scholar-Alternativen: [Scopus](https://www.scopus.com/), [Lens.org](https://www.lens.org/), [JSTOR](https://www.jstor.org/)
[OpenAlex](https://openalex.org/)
		- Indirekte Alternativen: [Scispace](https://scispace.com/), [Semantic Scholar](https://www.semanticscholar.org/), [ResearchGate](https://www.researchgate.net/)
	- Scholar-Alternativen mit API: [DBLP API](https://dblp.org/faq/How+to+use+the+dblp+search+API.html) ([DBLP SPARQL](https://sparql.dblp.org/)), [BASE API](https://api.base-search.net/), [Scopus API](https://dev.elsevier.com/api_docs.html), [Lens API](https://docs.api.lens.org/), [JSTOR programmatic access](https://labs.jstor.org/developers/), [OpenAlex API](https://docs.openalex.org/how-to-use-the-api/api-overview)
		- Indirekte Alternativen mit API: [Semantic Scholar](https://www.semanticscholar.org/product/api) (NOT: Scispace, ResearchGate)
- Fortgeschrittene Websuchen: Google [Advanced Search](https://www.google.com/advanced_search) (Liste of [Search Operators](https://ahrefs.com/blog/google-advanced-search-operators/)) | Google [Advanced Image Search](https://www.google.com/advanced_image_search)
	- Clean Google Search result URLs: [URL clean](https://urlclean.com/)
- KI-gestützte Literaturrecherche: [ResearchRabbit](https://www.researchrabbit.ai/), [Open Knowledge Maps](https://openknowledgemaps.org/), [Connected Papers](https://www.connectedpapers.com), [Consensus](https://consensus.app/search/), uvm.
	- Weitere Referenzen: [Georgetown Univ.-Bib. Liste](https://guides.library.georgetown.edu/ai/tools)
- Drei Informatik-Primärquellen: **[SpringerLink](https://link.springer.com/)**, **[ACM](https://dl.acm.org/)**, **[IEEE](https://ieeexplore.ieee.org/Xplore/home.jsp)**
- **[Publish or Perish](https://harzing.com/resources/publish-or-perish)**: Desktop Applikation mit intergrierten Autoren-Metriken
- Suche in mehreren PDFs (ohne Indexierung)
	- CLI: **[ripgrep-all](https://github.com/phiresky/ripgrep-all)** \[**choco install ripgrep-all**\], **[SeekFast](https://seekfast.org/download-seekfast)**
	- Alternative: unten im Abschnitt [Kostenlose Alternativen](#kostenlose-alternativen) die Abschnitte "Desktop Search Engine" und "Document Management Systeme"
- Fancy Cloud-/AI-Stuff (€): **[scite\_](https://scite.ai/)**, **[Iris.ai](https://the.iris.ai/)**, [DistillerSR](https://www.distillersr.com/)
- Anti-Paywall
	- Ausgangsbasis: Google Scholar, etc. pp., dort kein PDF sondern nur Link des Publishers, dort teuer
	- Rechtlicher Hintergrund: Webartikel [Was dürfen Sie nach Urheberrecht wirklich kopieren?](https://www.kopierermiete.de/news/18/04/was-duerfen-sie-nach-urheberrecht-wirklich-kopieren)
	- WICHTIG Anti-Paywall #1: Recherchieren Sie aus dem Netzwerk Ihrer Hochschule heraus (VPN) ⚠️
		- Die [Hochschul-Bibliothek](https://www.oth-aw.de/hochschule/ueber-uns/einrichtungen/bibliothek/suchen-und-finden/) schließt Verträge mit den Verlagen, Literaturdatenbanken, elektronischen Zeitschriften und verschiedenen E-Book-Portalen
		- Der Zugang, bspw. **SpringerLink** ✔️ und **Hanser ✔️**, ist i.d.R. IP-basiert, verwenden Sie deswegen VPN wie von der [Hochschul-Bibliothek](https://www.oth-aw.de/hochschule/ueber-uns/einrichtungen/bibliothek/suchen-und-finden/digitale-bibliothek/) beschrieben
		- Größte Lücke an der OTH-AW in Hinsicht _Informatik_-Literaturrecherche: Sie haben **KEINEN Zugang zu IEEE ❌ und ACM** ❌ (Warum? Gilt als zu teuer für uns. 😞)
	- WICHTIG Anti-Paywall #2: Kostenlose PrePrint-Fassungen eruieren 1. **Fragen Sie den Erstautor** oder die Erstautorin per **E-Mail** ⚠️ oder 2. per **ResearchGate** ⚠️ nach einer (Preprint-)Fassung. **Nur Mut**!
	- Anti-Paywall #3: Bücher und Publikationen gibt es auch als Papier, sogar kostenlos In der Bib Ihres Vertrauens 😦
		- Und kein „Mimimi“, an dieser Stelle! Fernleihe gibt es aus, fei echt.
	- Anti-Paywall #4: Legale Umgehung
		- Indirektes Entfernen, wirksam für „Soft-Paywalls“ mittels Popup/Overlay: **[readermode](https://readermode.io/)** ([Chrome](https://chrome.google.com/webstore/detail/reader-mode/llimhhconnjiflfimocjggfjdlmlhblm/))
		- Für wissenschaftliche Fachartikel: **[unpaywall.org](https://unpaywall.org/)** ([Chrome](https://chrome.google.com/webstore/detail/unpaywall/iplffkdpngmdjhlpjmppncnlhomiipha/), [Firefox](https://addons.mozilla.org/firefox/addon/unpaywall/))⚠️ sowie [Open Access Button](https://openaccessbutton.org/), [ScienceOpen](https://www.scienceopen.com/) und [CORE](https://scolary.com/tools/core) (= COnnecting REpositories)
		- Für journalistische Webartikel: **[12ft.io](https://12ft.io/)**
	- Rechtlich kritische Umgehung: Themenkomplex [Guerillia Open Access](https://archive.org/stream/GuerillaOpenAccessManifesto/Goamjuly2008_djvu.txt) und [Schattenbibliothek](https://www.google.com/search?q=schattenbibliothek) (Sci-Hub, Library Genesis, b-ok / Z-Library, Anna’s Archive und abgeschaltete Formen wie Bookfi)
		- [Rechtliche Einordnung](https://de.wikipedia.org/wiki/Schattenbibliothek#Rechtliche_Einordnung)
		- Webartikel [Schattenbibliotheken: Ein Krisensymptom der Wissenschaft](https://irights.info/artikel/schattenbibliotheken-ein-krisensymptom-der-wissenschaft/28663)
		- Journalartikel [Who's downloading pirated papers? Everyone](https://www.science.org/doi/10.1126/science.352.6285.508)
	- **Zusammenfassung** Ihres Informatik-Standard-Methodenkoffers zur **Literaturbeschaffung**:
		- ⚠️: **Google Scholar, VPN: SpringerLink/Hanser, höfliche E-Mail-Nachfragen, ResearchGate, Bib besuchen (fei echt), unpaywall.org**
- Read-it-Later
	- (Remark: Pocket-like! But Pocket shut down in 2025.)
	- Cloud: [Raindrop](https://raindrop.io/), [Notion](https://www.notion.com)
	- Web/Self-Hosted: [karakeep](https://karakeep.app/), [shiori](https://github.com/go-shiori/shiori)
	- (Außerdem die OneNote-Alternativen unter [Kostenlose Alternativen](#kostenlose-alternativen), wie Evernote)
- Persönliches Wissensmanagement / Zettelkasten / Notizen
	- **[Obsidian](https://obsidian.md/)** \[**choco install obsidian**\]: Zettelkasten und Notizen ([Obsidian **Video**-Tutorial: **Zettelkasten** für Beginner](https://www.youtube.com/watch?v=svqJ8BUh8mU))
	- **[Notion](https://www.notion.so/)** \[**choco install notion**\]: Notizen und Kollaboration
	- (Gegenüberstellung von [Obsidian vs. Notion](https://mattgiaro.com/zettelkasten-obsidian-notion/), aus der Perspektive Zettelkasten)
	- Vgl. ggf. zusätzlich die OneNote-Alternativen im Abschnitt [Kostenlose Alternativen](#kostenlose-alternativen)
- [Speed Reading](https://www.amazon.de/dp/3868828710/) / Schnelllesen / [RSVP](https://elvers.us/perception/rsvp/) / [Spritz](https://www.technology.org/2014/03/19/spritz-speed-reading-apps-prose-cons/):
	- Browser bookmarklet: **[jetzt](https://ds300.github.io/jetzt/#install)** ⭐
	- CLI/Console: [speedread](https://github.com/pasky/speedread)
- Weiterführende Quellen: [Tools for Academic Research](https://tools.kausalflow.com/tools/) ([lineare Variante](https://github.com/emptymalei/awesome-research))

## Portable Apps

Disclaimer: Einsatz kann in Unternehmen verboten sein, selbst wenn diese rein technisch sogar ausführbar sind!

- Portable Apps Repositories:
	- [PortApps.io](https://portapps.io/apps/)
	- [Portable Freeware](https://www.portablefreeware.com/)

## Generative KI

Die Verwendung von generativer KI zur Text-Erstellung Ihrer Abschlussarbeit ist Ihnen durch meine eigenen Policies untersagt. Dennoch können Sie sich die diversen Werkzeuge zu Nutzen machen, bspw. als persönlicher KI Tutor.

- AI-enabled Browser: Perplexity [Comet](https://comet.perplexity.ai/), [Sigma](https://www.sigmabrowser.com/), [Fellou](https://fellou.ai/), Arc [Max](https://arc.net/max), Opera [Aria](https://www.opera.com/de/features/aria), Microsoft Edge+Copilot
	- Mac-only: [Dia](https://www.diabrowser.com/)
	- Disbling AI features in Browsers: [Just the Browser](https://justthebrowser.com/)
- Als Extension:
	- in Browsern:
		- Grammatik: [LanguageTool](https://languagetool.org/de/chrome)
		- LLM u.a. für GMail: [Halist AI](https://chromewebstore.google.com/detail/halist-ai/fbpfkdadaghhgfcnaljbkjmfaaclohdb)
		- Weitere Referenzen: [Tooltivity-Liste](https://tooltivity.com/categories/ai)
	- in Thunderbird:
		- [ThunderAI](https://addons.thunderbird.net/en-US/thunderbird/addon/thunderai/)
- Desktop-Apps / AI Tool Installer:
	- Universell: **[pinokio](https://pinokio.computer/)**, [SEAIT](https://github.com/diStyApps/seait/)
- Text-to-Text:
	- LLM Model-Benchmark: [What LLM Provider](https://whatllm.vercel.app/) | [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) ([Method](https://huggingface.co/docs/leaderboards/open_llm_leaderboard/about)) sowie [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)
		- LLM Modelle mit DE-Unterstützung: [Webartikel](https://medium.com/@oledawidzinski/deutschsprachige-open-source-llms-als-alternative-zu-chatgpt-und-co-8ecbcf6ab96d) (u.a. Mistral-Nemo-Instruct-2407, DiscoLM_German_7b_v1, SauerkrautLM, …, Qwen2-7B-Instruct, Llama3-DiscoLeo-Instruct-8B, …)
		- Long-Term Context LLM / Personalized AI: [MemGPT](https://memgpt.ai/)
		- Agent AI: **[Letta](https://github.com/letta-ai/letta)**
	- Desktop/Local/Offline: **[Msty](https://msty.app/)** ⭐, **[LM Studio](https://lmstudio.ai/)** ⭐ \[**choco install lm-studio**\], **[Witsy](https://witsyai.com/)** ⭐ \[**choco install witsy**\], [AnythingLLM](https://anythingllm.com/), Nomic [gpt4all](https://github.com/nomic-ai/gpt4all) \[**choco install gpt4all**\], [Jan AI](https://jan.ai) \[**choco install jan**\] und andere
		- Local [OpenAI-compatible API](https://platform.openai.com/docs/api-reference/chat) Server: [LM Studio OpenAI-compatible API server](https://lmstudio.ai/docs/api/openai-api), [vLLM OpenAI-compatible API Server](https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html), [Msty Local AI Service](https://docs.msty.app/how-to-guides/make-local-ai-service-available-on-the-network), [gpt4all API Server](https://docs.gpt4all.io/gpt4all_api_server/home.html), [Jan.ai Cortex Local API Server](https://cortex.so/docs/quickstart/) ([API](https://cortex.so/api-reference/))
			- Docker: [LocalAI](https://localai.io/): Local family AI, full-stack = All-in-One: LLMs, Text to Speech, Speech to Text, Function calling, Image generation, Embedding server
		- Let LLMs run code locally: [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter)
	- WebUI/Local/Offline: [pinokio](https://pinokio.co/)
		- **[Open WebUI](https://openwebui.com/)** ⭐
		- [Text Generation WebUI](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fcocktailpeanut%2Foobabooga.pinokio) (both best installed via )
	- Embedded/Local/Offline: [vLLM](https://github.com/vllm-project/vllm)
	- Desktop/Cloud-only/Online: **[Noi](https://github.com/lencx/Noi)**
	  - Single Vendor: Unofficial **[ChatGPT Desktop](https://github.com/lencx/ChatGPT)** \[**choco install chatgpt**\], Official **[Claude Desktop](https://claude.ai/download)** \[**choco install claude**\], Official **[Perplexity Windows App](https://apps.microsoft.com/detail/xp8jnqfbqh6pvf)** (sowie Unofficial Inulute [Perplexity AI Desktop](https://pplx.inulute.com/download/))
	- more: [basran](https://github.com/hyperonym/basaran), [LocalAI](https://github.com/mudler/LocalAI), [Xorbits Inference](https://github.com/xorbitsai/inference) 
	- Search-Chatbots: [**perplexity**.ai](https://www.perplexity.ai/) ⭐ (mit „Focus: Academic“)
		- Weitere Nennenswerte: Anthropic **[Claude](https://www.anthropic.com)**, Google [Gemini](https://gemini.google.com/), OpenAI [ChatGPT](https://openai.com/blog/chatgpt/), Meta [Llama](https://llama.meta.com/), [HuggingChat](https://huggingface.co/chat/), Opera [Aria](https://www.opera.com/features/aria), [character.ai](https://beta.character.ai/), …
	- KI-Suche
		- [**you**.com](https://you.com/), [Andi](https://andisearch.com), Microsoft [Bing](https://bing.com/new), OpenAI [SearchGPT](https://openai.com/index/searchgpt-prototype/), …
	- Data Science
		- [**WolframAlpha** Chat Notebooks in der Wolfram Cloud](https://www.wolframcloud.com/) ⭐ ([Anleitung](https://writings.stephenwolfram.com/2023/06/introducing-chat-notebooks-integrating-llms-into-the-notebook-paradigm/))
	- Summarizer
		- Ask your Document: [AskYourPDF](https://askyourpdf.com), [ChatPDF](https://www.chatpdf.com/), [PDF.ai](https://pdf.ai/), …
		- DIY-Helfer
			- Prompt Splitter: [chatgpt-**prompt-splitter**](https://chatgpt-prompt-splitter.jjdiaz.dev) für großen Text-Input (derzeit sind nur Chunks von jeweils ein paar Tausend Zeichen erlaubt)
			- Text-Extraktion aus PDF: **pdftotext** aus den [xpdf-utils](http://www.xpdfreader.com) \[**choco install xpdf-utils**\]
		- YouTube Summarizer (mittels GPT): **[Glasp](https://glasp.co/youtube-summary)**
- Text-to-...: ([Auswahlhilfe](https://llmselector.vercel.app/))
	- Text-to-Code:
		- Dev/FOSS-Models: Facebook [Llama](https://www.llama.com/llama-downloads/), OpenAI [gpt-oss](https://openai.com/index/introducing-gpt-oss/), Google [gemma](https://huggingface.co/google), [DeepSeek](https://huggingface.co/deepseek-ai), xAI [grok](https://huggingface.co/xai-org), [Qwen](https://huggingface.co/Qwen), [Mistral](https://huggingface.co/mistralai) (Mistral [Commercial vs. OSS](https://docs.mistral.ai/getting-started/models)), TII [Falcon](https://huggingface.co/tiiuae), BigScience [BLOOM](https://huggingface.co/bigscience/bloom)
			- AI-Coder Model-Benchmark: [Eval Plus](https://evalplus.github.io/leaderboard.html)
		- Desktop/Local/Offline: **[Msty](https://msty.app/)** ⭐, **[LM Studio](https://lmstudio.ai/)** ⭐
		- WebUI/Local/Offline: [bolt.diy](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fpinokiofactory%2Fbolt), [autogpt](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fpinokiofactory%2Fautogpt) (via [pinokio](https://pinokio.co/))
		- Cloud/freemium: [DeepSeek Chat](https://chat.deepseek.com/) ,Online [Eden AI](https://www.edenai.co/), [uvm.](https://codesubmit.io/blog/ai-code-tools/)
		- Nennenswerte andere Dev-Tools: [dir-assistant](https://github.com/curvedinf/dir-assistant)
		- Weiterführende Referenzen: [Awesome AI-Powered Developer Tools](https://github.com/jamesmurdza/awesome-ai-devtools) | [Awesome Code-AI](https://github.com/sourcegraph/awesome-code-ai)
	- Text-to-SQL:
		- Foundational Models: [DuckDB NSQL](https://github.com/NumbersStationAI/DuckDB-NSQL)
		- Tutorials: AWS Machine Learning [Build a robust text-to-SQL solution ](https://aws.amazon.com/de/blogs/machine-learning/build-a-robust-text-to-sql-solution-generating-complex-queries-self-correcting-and-querying-diverse-data-sources/), LlamaIndex [Text-to-SQL Guide with Jupyter](https://docs.llamaindex.ai/en/stable/examples/index_structs/struct_indices/SQLIndexDemo/), IBM Watson [Generating SQL from text with LLMs](https://developer.ibm.com/tutorials/awb-text-to-sql-using-llms/)
	- Text-to-Image:
		- AI-Image-Generator Model-Benchmark: Artificial Analysis [Image AI Model & Provider Leaderboard](https://artificialanalysis.ai/text-to-image) | [Benchmarking-Awesome-Diffusion-Models](https://github.com/Schuture/Benchmarking-Awesome-Diffusion-Models)
		- Dev/FOSS Models: **[Stable Diffusion](https://github.com/CompVis/stable-diffusion)**, **[FLUX.1](https://github.com/black-forest-labs/flux)**
		- Desktop/Local/Offline: Lykos **[Stability Matrix](https://lykos.ai/downloads)** ⭐ (Tutorial: [Using FLUX.1 locally](https://www.kdnuggets.com/using-flux-1-locally))
			- Stability Matrix ist ein 1-Stop-Shop für alle anderen Werkzeuge wie bspw.: Stable Diffusion WebUI [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge) bzw. [reForge](https://github.com/Panchovix/stable-diffusion-webui-reForge), [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
			- Disclaimer: Manche Text-to-Image Werkzeuge benötigen (Stand 2025) eine NVidia RTX als Hardware-Voraussetzung
			- Bonus-Hinweis: Für Stable Diffusion WebUI, und dessen Derivate, kann man dessen REST-API (aka **sdapi**) mit dessen Kommandozeilenparameter `--api` aktivieren
				- Diesen `--api` Parameter kann man auch in Stability Matrix (unter dessen `Launch Options` für Stable Diffusion WebUI) leicht ergänzen (per `Extra Launch Arguments`)
				- Die aktivierte **sdapi** läuft dann bspw. unter http://127.0.0.1:7860/sdapi/v1/txt2img
		- WebUI/Local/Offline: [MFLUX-WWebUI](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fpinokiofactory%2FMFLUX-WEBUI) (via [pinokio](https://pinokio.co/))
		- Cloud/freemium-with-API: [Playground](https://playground.com/design/pricing), [PicoGen](https://picogen.io/), [Pollinations AI](https://pollinations.ai/)
		- Cloud/freemium: [Deep Dream Generator](https://deepdreamgenerator.com/) ([old version](https://deepdreamgenerator.com/generator?old-tools=1)), [Dezgo](https://dezgo.com/text2image/sdxl), [Stable Diffusion Online](https://stablediffusionweb.com/) (10img/d; mit Wasserzeichen), [NightCafe](https://creator.nightcafe.studio/), [WPimages](https://www.wpimagines.com/), [AI Image Generator](https://www.aiimagegenerator.org/), [uvm.](https://easywithai.com/best-free-ai-image-generators/)
		- Cloud/€€€/Subscriptions: **[OpenArt](https://openart.ai/create)** ⭐, [fal](https://fal.ai/), [dreamina](https://dreamina.capcut.com/ai-tool/home/?type=image), OpenAI [**DALL·E** 2](https://labs.openai.com/waitlist), **[Midjourney](https://www.midjourney.com/)**, [craiyon](https://www.craiyon.com/) (früher: „DALL·E mini“), Google [Imagen](https://imagen.research.google/), Adobe [Firefly](https://www.adobe.com/products/firefly.html) …
	- Text-to-Video: [synthesia](https://www.synthesia.io), [dreamina](https://dreamina.capcut.com/ai-tool/home/?type=video), [kaiber.ai](https://kaiber.ai), … , China: [Kling](https://kling.kuaishou.com/en)
		- WebUI/Local/Offline: [CogStudio](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fpinokiofactory%2Fcogstudio), [FramePack](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fpinokiofactory%2FFrame-Pack), [fp-studio](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2FFP-Studio%2Ffp-studio), [Wan](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fpinokiofactory%2Fwan) (via [pinokio](https://pinokio.co/))
	- Text-to-Slides: **[Gamma](https://gamma.app/)** ⭐, [Felo Slides](https://felo.ai/agents/felo-slides-qP4dLw7kMv9ZuG5FnX8cH1), [SlidesPilot](https://www.slidespilot.com/), [SlideSpeak](https://slidespeak.co/), [ChatBA](https://www.chatba.com/), [Presentation Intelligence](https://www.pi.inc/), [Slidesgo](https://slidesgo.com/), …
		- Academic: [ChatSlide](https://chatslide.ai/) (formerly: DrLambda)
		- Local: «tbd» ([AutoPresent](https://github.com/para-lost/AutoPresent))
	- Text-to-Visuals (for presentations): [Napkin AI](https://app.napkin.ai/)
	- Text-to-Quiz: [Quizalize](https://app.quizalize.com/pricing), …
	- Text-to-Speach (TTS): [NaturalReader](https://www.naturalreaders.com/online/), [TTSMaker](https://ttsmaker.com/), [Murf.AI](https://murf.ai/text-to-speech), …
	- Text-to-Sound: [boomy](https://boomy.com/), [Suno AI](https://app.suno.ai/), [Vocaloid](https://www.vocaloid.com/en/vocaloid6/), Google [Instrument Playground](https://artsandculture.google.com/experiment/instrument-playground/8QFo2oQr2uT3pg?hl=en), …
		- WebUI/Local/Offline: [YuE](https://pinokio.co/item.html?uri=https%3A%2F%2Fgithub.com%2Fpinokiofactory%2Fyue) (via [pinokio](https://pinokio.co/))
	- Text-to-3D / Image-to-3D: [csm.ai](https://www.csm.ai) (zzgl. €: [3D AI Studio](https://www.3daistudio.com))
	- AI-Suites/API-centric/Pay-as-you-Go: **[Fireworks AI](https://fireworks.ai/)**, [Replicate](https://replicate.com/)
	- Weiterführende Referenzen: [There is an AI for that](https://theresanaiforthat.com/most-saved/) | [There's an AI](https://theresanai.com/)
- IT-Security:
	- [WormGPT](https://thehackernews.com/2023/07/wormgpt-new-ai-tool-allows.html)
- Prompt Builder:
	- Cloud: gptforwork [OpenAI GPT prompt generator](https://gptforwork.com/tools/prompt-generator)
- Prompting Desktop Integration:
	- [Razer AI Launcher](https://mysupport.razer.com/app/answers/detail/a_id/15016) (Benötigt Razer Maus; Prompt Launcher ist dann Teil von **Synapse**)
	- [Logi AI Prompt Builder](https://www.logitech.com/software/logi-ai-prompt-builder.html) (Benötigt Logitech Maus; Prompt Builder ist dann Teil von **Logi Options+**)
	- Weiterführende Quellen: [Awesome **ChatGPT Prompts**](https://github.com/f/awesome-chatgpt-prompts)
- Weiterführende Quellen
	- Werkzeugsammlungen: **[FutureTools](https://www.futuretools.io)** | [Awesome AI Tools](https://tools.awesomechatgpt.com) #1 | [Awesome AI Tools](https://github.com/mahseema/awesome-ai-tools) #2 | Altern [Awesome AI Tools](https://github.com/mahseema/awesome-ai-tools) #3 | [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) #1 | [Awesome Generative AI](https://github.com/filipecalegario/awesome-generative-ai) #2 | [Awesome AGI](https://github.com/EmbraceAGI/Awesome-AGI) | [Awesome GPT](https://github.com/formulahendry/awesome-gpt) | [Awesome GPT-4](https://gpt4.tools) | [Awesome Bots](https://github.com/DopplerHQ/awesome-bots)

## LaTeX & PDF

- DISCLAIMER: **[typst](https://typst.app/) vs. LaTeX**? Mit typst gibt es eine moderne Typesetting-Variante zu latex, die aber technisch völlig eigenständig ist.
	- Überlegen Sie ggf. Publikationen oder Abschlussarbeiten in typst zu schreiben; nur fehlt dann ggf. die einfache Vorlage (aber mind. [IEEE](https://typst.app/universe/package/charged-ieee/) gibt es sowie erste Drafts zu [ACM](https://typst.app/universe/package/clean-acmart))
	- Mit [touying](https://touying-typ.github.io/) gibt es eine gute Altternative zu latex-beamer in typst
	- Weiterführende Quellen: [Typst Examples Book](https://sitandr.github.io/typst-examples-book/book/), [Awesome Typst](https://github.com/qjcg/awesome-typst)
	- "This being said ..." jetzt zurück zum wohlbekannten LaTeX:
- Einstieg:
	- LaTeX: Overleaf **[Learn LaTeX in 30 Minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)** sowie **[How to Write a Thesis in LaTeX](https://www.overleaf.com/learn/latex/How_to_Write_a_Thesis_in_LaTeX_(Part_1)%3A_Basic_Structure)**
		- Weiteres Einstiegsmaterial:	**[A simple guide to LaTeX – Step by Step](https://latex-tutorial.com/tutorials/)** | **[Wikibooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX)**
		- Korrekte Anführungszeichen ⚠️: lese **[Quotation Marks](https://latex.silmaril.ie/formattinginformation/quotes.html)** von Peter Flynn oder **[Formatting](https://www.andy-roberts.net/latex/formatting/)** von Andrew Roberts bzw. verwende **[csquotes](https://tex.stackexchange.com/tags/csquotes/info)** mit **\\enquote{..}** ⭐
		- Wichtige Einordnung: [The **TeX family tree**: LaTeX, **pdfTeX**, **XeTeX**, LuaTeX and ConTeXt](https://de.overleaf.com/learn/latex/Articles/The_TeX_family_tree%3A_LaTeX%2C_pdfTeX%2C_XeTeX%2C_LuaTeX_and_ConTeXt) ⚠️
		- Common Anti-Patterns: enthalten in [An **essential guide** to LATEX2e usage](http://mirrors.ctan.org/info/l2tabu/english/l2tabuen.pdf) ⭐
	- BibTeX/Literaturverzeichnis: **[Tame the BeaST](http://tug.ctan.org/info/bibtex/tamethebeast/ttb_en.pdf)**
		- Wichtige Einordnung: **[bibtex vs. biber and biblatex vs. natbib](https://tex.stackexchange.com/questions/25701/bibtex-vs-biber-and-biblatex-vs-natbib)** ⚠️
		- Common Anti-Patterns: **[How to not mess up your bibliographies with Bibtex](https://clauswilke.com/blog/2015/10/02/bibtex/)** (2015) von Claus Wilke ⭐
		- Nennenswerte biblatex-Erweiterung: **[biblatex-ext](https://github.com/moewew/biblatex-ext)** ([CTAN](https://ctan.org/tex-archive/macros/latex/contrib/biblatex-contrib/biblatex-ext)) sowie darin enthalten **biblatex-ext-oa** für Open Access Symbole
	- Installation: [LaTeX-**Installationsmöglichkeiten** für Linux, macOS, Windows und Cloud-Optionen](https://www.latex-project.org/get/) unter latex-project.org
	- Vorlagen: Es gibt [LaTeX-**Vorlagen der OTH-AW**](https://www.oth-aw.de/latex/) bzw. Fakultät EMI für die Abschlussarbeit
	- Groß-/Kleinschreibung von engl. Überschriften: **[Capitalize My Title](https://capitalizemytitle.com/style/Chicago/)** ⭐
	- RGB-Schwarz vs. CMYK-Schwarz
		- Ergänzen Sie in LaTeX unbedingt die **cmyk**-Option des **xcolor**-Packages ⚠️
		- Ohne diese Option handelt es sich auf allen Seiten um RGB-Schwarz, die im Druck als **Farbseiten** zählen und das wird teuer. Mit dieser Option sparen Sie im Copy-Shop bares Geld.
		- (Ein RGB-Schwarz – mit Werten 0,0,0 – wird i.d.R. in ein CMYK-Schwarz konvertiert, dessen Werte 75C, 68M, 67Y und 90K sind; was übrigens auch als Tiefschwarz bezeichnet wird. Nur mit gesetzter cmyk-Option wird ein RGB 0,0,0, in ein Druckkosten-effizientes CMYK 0,0,0,100 konvertiert.)
		- In die LaTeX-Vorlage der OTH habe ich das bereits reingepatcht, aber haben Sie ein Auge darauf.
- **[MikTeX](http://miktex.org)**: Umgebung für LaTeX unter Windows ⭐
	- Stellen Sie nach der Installation den Package Manager auf einen Webmirror (FTP) Ihrer Wahl ein, damit zusätzlich benötigte Packages automatisch installiert werden können.
	- (Unter Windows bspw. mittels chocolatey: **choco install miktex.install '"/Set:basic"'** sowie **choco install synctex**)
	- Alternative: [TeX Live](https://tug.org/texlive/windows.html) \[choco install texlive\], [tectonic](https://tectonic-typesetting.GitHub.io/) \[choco install tectonic\]
- **[Sumatra PDF](https://www.sumatrapdfreader.org)** \[**choco install sumatrapdf.install**\] ⭐: PDF Viewer
	- Für LaTeX-Zwecke besser geeignet als Adobe Reader, weil er aus einem TeX-Editor heraus an die korrekte Stelle springt… sehr bequem!
	- Außerdem blockiert Sumatra die angezeigte Datei nicht auf Betriebssystemebene, damit ist die Datei trotz Lesezugriff durch latex neu generierbar/schreibbar
	- Nennenswerte Alternative: **[pympress](https://github.com/Cimbali/pympress/releases)** als PDF-Viewer (auch für Windows)
- **[TeXstudio](https://www.texstudio.org/)** \[**choco install texstudio.install**\] ⭐: Ein Fork von Texmaker, früher auch TexMakerX genannt (m.E. weit besser als TeXworks)
	- Warnhinweis: Sowohl MikTeX als auch Sumatra PDF vor den Editoren installieren, da diese sich tlw. beim ersten Start gleich für beides konfigurieren
	- Alternativen: [TeXnicCenter 2.0](https://www.texniccenter.org) \[**choco install texniccenter**\], [Kile](https://kile.sourceforge.io/) \[**choco install kile**\], [Texmaker](https://www.xm1math.net/texmaker/) \[**choco install texmaker**\] sowie der in MikTeX und TeX Live enthaltene [TeXworks](https://tug.org/texworks) | speziell unter Mac/iOS: [Texifier](https://www.texifier.com/) oder [TeXShop](https://pages.uoregon.edu/koch/texshop/) | Gesamtübersicht: [LaTeX Editors/IDEs](https://tex.stackexchange.com/questions/339/latex-editors-ides)
- **[TeXiFy](https://plugins.jetbrains.com/plugin/9473-texify-idea)** ⭐ als Plug-In für InteliJ IDEA von Jetbrains (Studis haben die Lizenz für IDEA kostenlos)
	- Works with? MiKTeX or TeX Live! Inkl. Integration mit dem PDF Viewer plugin für IDEA.
	- Alternativen: Es gibt auch für VS Code die Extension [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop), welche aber nur mit TeX Live harmoniert
- **[Zotero](https://www.zotero.org/)** \[**choco install zotero**\] ⭐: Verwaltung der Literatur, u.a. PDFs sowie BibTeX
	- Anleitungen: [Quick Start Guide](https://www.zotero.org/support/quick_start_guide), [Integrating Zotero with Word](https://researchguides.gonzaga.edu/zotero/word)
	- Alternativen: [JabRef](https://www.jabref.org) \[**choco install jabref.install --ignore-dependencies**\] | [Mendeley Reference Manager](https://www.mendeley.com/reference-management/reference-manager) \[**choco install mendeley-reference-manager**\]
	- Kommerzielle Alternativen: Citavi | EndNote, …
	- Cloud-Alternative insb. im Zusammenspiel mit Overleaf: **[CiteDrive](https://www.citedrive.com/)**
- **[Overleaf](https://www.overleaf.com)** ⭐: Kostenlos LaTeX-Dokumente in der Cloud editieren/kompilieren
	- Zumindest mit einer „Compile timeout“ von bis zu 1 Minute
	- Geniale Integration von **[LanguageTool](https://languagetool.org/overleaf)**, für Rechtschreibung und Grammatik, wenn es als Browser-Erweiterung installiert wurde
	- Tastaturkürzel: [Overleaf **Keyboard Shortcuts**](https://www.overleaf.com/latex/templates/overleaf-keyboard-shortcuts/pphdnzrwmttk)
	- Overleaf ist Open Source und man könnte sich den Overleaf-Server auch lokal selbst hosten: [github.com/overleaf/overleaf](https://github.com/overleaf/overleaf) ([Quick Start Guide](https://github.com/overleaf/toolkit/blob/master/doc/quick-start-guide.md))
	- (Vorlagen: bspw. [IEEE Conference](https://www.overleaf.com/latex/templates/ieee-conference-template/grfzhhncsfqn) (aber [IEEEtran HowTo](http://mirrors.ctan.org/macros/latex/contrib/IEEEtran/IEEEtran_HOWTO.pdf) ⚠️ lesen, u.a. sollte man shared affiliations nicht mehrfach aufführen), [PocketMod](https://www.overleaf.com/latex/examples/creating-pocketmods-with-latex/nqbhpnrkskrx) oder [Résumé/CV](https://de.overleaf.com/gallery/tagged/cv))
- TeX in git:
	- **[gitattributes](https://richienb.github.io/gitattributes-generator/)**-Generator (Obacht: LF-formatiert) von Richie Bendall: Das **COMMON**-Profil deckt LaTeX-Projekte ab
	- **[gitignore](https://www.toptal.com/developers/gitignore/)**-Generator (Obacht: LF-formatiert) von Toptal
- Sonstige Werkzeuge
	- **[pdfsizeopt](https://github.com/pts/pdfsizeopt)**: optimize the size of PDF files (with focus on PDFs created from TeX and LaTeX documents)
	- Die TeX-Pakete [cs-techrep](https://ctan.org/pkg/cs-techrep) ([Bsp.](https://mirrors.ctan.org/macros/latex/contrib/cs-techrep/template/cs-techrep-example-neumann.pdf)) und [iaria](https://ctan.org/pkg/iaria) ([Bsp.](https://mirrors.ctan.org/macros/latex/contrib/iaria/template/iaria-example-neumann.pdf)) sowie [iaria-lite](https://ctan.org/pkg/iaria-lite) ([Bsp.](https://mirrors.ctan.org/macros/latex/contrib/iaria-lite/template/iaria-lite-example-neumann.pdf)) sind Vorlagen von mir
	- Literaturverzeichnis:
		- [BibTeX Tidy](https://flamingtempura.github.io/bibtex-tidy/index.html): can fix inconsistent whitespace, remove duplicates, remove unwanted fields, and sort entries
		- DOI: **[doi2bib](https://www.doi2bib.org/)** für BibTeX | [DOI Citation Formatter](https://citation.crosscite.org/) bspw. für Word
		- [**ISBN**-Validator](https://0b10011.io/tools/isbn-validator.html)
		- [**ISSN**-Validator](https://journalseeker.researchbib.com/?action=issnChecker)
		- Deprecated:
			- BibTeX generator from URL: **[url-to-bibtex](https://url-to-bibtex.vercel.app/)** aber eigentlich nicht mehr MISC mit howpublished, sondern durch nunmehr ONLINE mit url und urldate!
	- Quality Check:
		- **[blackTeX](https://github.com/texworld/blacktex)** \[**pip install -U blacktex**\]: corrects some common [TeX anti-patterns](https://ctan.mirror.norbert-ruehl.de/info/l2tabu/english/l2tabuen.pdf)
	- Nennenswerte CTAN-Pakete:
		- Alle packages, welche ich in cs-techrep sowie iaria verwende!
		- [backnaur](https://ctan.org/pkg/backnaur) `\usepackage[altpo]{backnaur}`
		- [tcolorbox](https://ctan.org/pkg/tcolorbox): für [Poster](https://mirrors.ctan.org/macros/latex/contrib/tcolorbox/tcolorbox-tutorial-poster.pdf)!
			- Oder tcolorbox für hübsche Boxen zu Research Questions sowie Findings:
			```latex
			\usepackage[most]{tcolorbox}
			\tcbset{
				resques/.style={
					colback=white, 
					colframe=black, 
					boxrule=0.5pt, 
					sharp corners, 
					enhanced,  
					width=\linewidth,
					top=2pt, bottom=2pt, left=3pt, right=3pt,
					breakable, drop lifted shadow
				}
			}
			\newenvironment{resques}[1]{
				\begin{tcolorbox}[resques]
				\textbf{#1:}
			}{
				\end{tcolorbox}
			}
			```
			Und damit Research Questions oder Findings als:
			```latex
			\begin{resques}{RQ\,1}
			How does ...?
			\end{resques}
			\begin{resques}{Finding\,1}
			It occurs ...?
			\end{resques}
			```
			- Oder tcolorbox für hübschen Boxen zu LLM-Dialogen:
			```latex
			\usepackage[most]{tcolorbox}
			\usepackage{xcolor}
			\newtcolorbox{humanbox}{colback=blue!10!white,
			  title=Human, colframe=blue, left=1mm, right=1mm, top=1mm, bottom=1mm}
			\newtcolorbox{chatbotbox}{colback=green!10!white,
			  title=Chatbot, colframe=green, left=1mm, right=1mm, top=1mm, bottom=1mm}
			```
			Und damit LLM-Dialoge als:
			```latex
			\begin{humanbox}
			How can I format dialog between human and chatbot in LaTeX?
			\end{humanbox}
			\begin{chatbotbox}
			You can use tcolorbox to distinguish between speakers and visually separate their lines, as shown here.
			\end{chatbotbox}
			```
	- Open Science
		- Software referenzieren? **[Zenodo](https://zenodo.org/)** | [GitHub-Doku](https://docs.github.com/de/repositories/archiving-a-GitHub-repository/referencing-and-citing-content) (benötigt: GitHub! Derzeit GitLab nicht unterstützt.)
	- **[Tables Generator](https://tablesgenerator.com/)**: LaTeX tables generator using table data from a spreadsheet app
		- Kann neben LaTeX auch HTML, ASCII-Tabellen, Markdown und MediaWiki generieren
	- [**CubePDF** Utilities](https://www.cube-soft.jp/cubepdfutility/) \[**choco install cubepdfutility**\] ⭐: u.a. zum kostenlosen Löschen (sowie Extrahieren/Vereinigen) von Seiten aus einem PDF (bspw. zur Vorbereitung der 10Seiten-Vorabreview-Fassung), eine Funktion die aus dem Acrobat Reader ausgebaut ist und derzeit nur der Acrobat Pro Fassung vorbehalten ist
	- LaTeX to HTML: [Übersicht per **TeX-FAQ**](https://texfaq.org/FAQ-LaTeX2HTML)
		- tex4ht und [make4ht](https://github.com/michal-h21/make4ht) sind in MikTeX inkludiert: **make4ht filename.tex**
		- **[LaTeXML](https://math.nist.gov/~BMiller/LaTeXML/)** \[**choco install latexml**\]: [Getting Started](https://hackmd.io/@UoL-IWG/latexml)
	- PDF to HTML:
		- Adobe Acrobat Pro
		- **[pdf2htmlEX](https://pdf2htmlex.GitHub.io/pdf2htmlEX/)** \[[Docker](https://hub.docker.com/r/pdf2htmlex/pdf2htmlex)\]: [Quick Start](https://github.com/pdf2htmlEX/pdf2htmlEX/wiki/Quick-Start)
		- [**PDFMate** PDF Converter Free](https://www.pdfmate.com/pdf-converter-free.html) (kostenlose Version mit einem 3-Seiten-Limit)
	- LaTeX to Word
		- via LibreOffice/OpenOffice: tex4ht und [make4ht](https://github.com/michal-h21/make4ht) sind in MikTeX inkludiert: **make4ht --format odt filename.tex**
			- LibreOffice-Installation: **choco install libreoffice-still**
		- via PDF: Desktop: [pdf2docx](https://dothinking.GitHub.io/pdf2docx/quickstart.html) \[**pip install pdf2docx**\] | Cloud: [**pdf2docx**.com](https://pdf2docx.com)
- Weiterführende Quellen: **[Awesome LaTeX](https://github.com/egeerardyn/awesome-LaTeX)** | [Awesome fonts](https://github.com/brabadu/awesome-fonts)

## Markdown Publishing

- **[typst](https://typst.app/)** ⭐
	- Mit typst gibt es eine moderne Typesetting-Variante zu latex, die aber technisch völlig eigenständig ist.
	- HINWEIS: die eigenständige [typst Markup Syntax](https://typst.app/docs/reference/syntax/) (inkl. [Math mode](https://typst.app/docs/reference/math/)) ist eine Mischung aus [AsciiDoc](https://docs.asciidoctor.org/asciidoc/latest/syntax-quick-reference/) und [Markdown]() (bspw. MarkDown: Code-Blöcke und Listen | AsciiDoc: Überschriften sowie bold und italics | zzgl. [AsciiMath](https://asciimath.org/))
	- Einführung: [Typst Examples Book](https://sitandr.github.io/typst-examples-book/book/)
	- Cheat Sheet: [Typst Cheat Sheet](https://github.com/mewmew/typst-cheat-sheet)
	- Scientific Layouts: [IEEE](https://typst.app/universe/package/charged-ieee/) | [ACM](https://typst.app/universe/package/clean-acmart))
	- Weiterführende Quellen: [Awesome Typst](https://github.com/qjcg/awesome-typst)
- [Quarto](https://quarto.org/docs/output-formats/all-formats.html) unterstützt [Presentations](https://quarto.org/docs/presentations/)
	- Quarto ist ein Open-Source-System für wissenschaftliche und technische Veröffentlichungen, das auf Pandoc basiert.
	- Scientific Layouts: [IEEE](https://github.com/dfolio/quarto-ieee) | [ACM](https://github.com/quarto-journals/acm)
	- Weiterführende Quellen: [Awesome Quarto](https://github.com/mcanouil/awesome-quarto)
- Markdown Syntax:
	- Nennenswerte Markdown-Lücken? u.a. Tabellen und Fußnoten! Auch keine Auto-Links!
		- AsciiDoc, etwas älter als Markdown, sowie Typst schließen und unterstützen alle Markdown-Lücken! Markdown wurde explizit als simple Syntax geschaffen!
		- AsciiDoc als vollwertiges Dokumentationsformat für Technical Writing und für Multi-Channel Publishing (manpages, EPUB/HTML, DocBook, PDF), als [DocBook](https://tdg.docbook.org/)-Alternative; allerdings OHNE Layouting, Typographie oder Scripting
		- Typst als professionalles Textsatz-System / typsetting engine (PDF und nur [experimenteller HTML](https://typst.app/docs/reference/html/)-Support), d.h. inkl. Layout und Typographie, als
 [LaTeX](https://www.latex-project.org/)-Alternative; allerdings OHNE Multi-Channel-Intention, bpsw. kein EPUB und keine manpages
		- Vereinfacht: MarkDown/AsciiDoc/DocBook (Online) sowie typst/latex (Print), wobei DocBook/AsciiDoc offensichtlich auch eine Print-Ausdehnung haben
		- Weiterführende Infos: [lmptfy](https://www.perplexity.ai/search/new?q=Bitte+einen+ausführlichen+Vergleich+zu+AsciiDoc%2C+Markdown%2C+GFM%2C+Typst+sowie+LaTeX+und+DocBook.+Mit+historischer+und+konzeptioneller+Gegenüberstellung.+Und+Vergleichstabelle+von+gängigen+Elementen+zu+Markdown%2C+GFM%2C+AsciiDoc+und+Typst%2C+achte+dabei+auf+das+preformatting+der+Syntax+in+der+Tabelle.+Gehe+auch+auf+den+Math+Mode+ein%2C+sowie+AsciiMath.)
	- Standardisierung: [CommonMark](https://commonmark.org/) ([Spec](https://spec.commonmark.org/current/)) (Auch keine Tabellen und Fußnoten!)
	- Webartikel [The Ultimate Markdown Cheat Sheet for Technical Writers and Documentation Engineers](https://medium.com/@kevinteaches/the-ultimate-markdown-cheat-sheet-for-technical-writers-541dbb9fd53c)
	- [GitHub Flavored Markdown](https://github.github.com/gfm/) (GFM), inkl. Tabellen (Weiterhin fehlend? u.a. Fußnoten!)

## Schreiben

- Einführungen:
	- [memdesign](http://mirrors.ctan.org/info/memdesign/memdesign.pdf) ⭐: introduction to the business of book design
- ⚠️ Lernen Sie 10-Finger-schreiben ⚠️
	- Am besten jetzt nicht mehr mit QWERTZ-/QUERTY-basiertem 10-Finger-System anfangen, sondern gleich [Dvorak](https://de.wikipedia.org/wiki/Dvorak-Tastaturbelegung) \[EN\] lernen oder eines aus der [Neo-Familie](<https://de.wikipedia.org/wiki/Neo_(Tastaturbelegung)>) \[DE\] ([Neo2, Bone, Mine](https://neo-layout.org/Layouts/) oder [AdNW](http://adnw.de/))
	- für Dvorak: [RapidTyping](https://rapidtyping.com/) als Windows-Desktop-Werkzeug, bzw. Online das [Dvorak keyboard training](https://learn.dvorak.nl/), das [Programmer Dvorak typing tutorial](http://programmer-dvorak.appspot.com/), uvm.
	- für Neo: v.a. unter Linux mittels KTouch oder unter Windows [diverse Typing Tutors](https://typingsoft.com/all_typing_tutors.htm), von denen allerdings m.E. keiner auf Neo spezialisiert ist; also gerne auch den [RapidTyping](https://rapidtyping.com/) verwenden
	- (für QWERTZ/QUERTY, falls ich Sie nicht davon abhalten konnte: [TIPP10](https://www.tipp10.com/) \[**choco install tipp10**\] sowie [diverse andere Typing Tutors](https://typingsoft.com/all_typing_tutors.htm))
	- Ich selbst verwende Dvorak (allerdings gab es Neo im Jahr 1999 noch nicht, es entstand erst 2004, da war mein Studium schon fast vorbei, bzw. wurde Neo erst 2010 mit Neo2 konsolidiert)
	- [Tastatur-Tastenkürzel unter Windows](https://www.digitalcitizen.life/keyboard-language-shortcut/):
		- Drücke **Win + Leertaste**, um durch die Sprachen zu blättern.
		- Alt-Shift/Ctrl-Shift-Einstellungen: Abschnitt "Erweiterte Tastatureinstellung" » Element "Tastenkombination für Eingabesprachen"
- Rechtschreibprüfung?
	- Word / OpenOffice.org / LibreOffice / etc.
		- Benutzbar auch für LaTeX ⚠️ indirekt per Windows [TeX2RTF](https://www.ctan.org/pkg/tex2rtf) oder Linux [latex2rtf](http://latex2rtf.sourceforge.net/)
	- Dienste wie [Scribbr](https://www.scribbr.de/rechtschreibpruefung/)
- **[Grammarly](https://www.grammarly.com/)** \[**choco install grammarly-for-windows**\]: Grammatik-Prüfung, sehr mächtig, KI-gestützt, aber nur für Englisch!
	- Auch [als MS Office Extension](https://www.grammarly.com/office-addin)
	- Alternative: **[Ginger](https://www.gingersoftware.com/)** \[**choco install gingerwriter**\]
- **[LanguageTool](https://languagetool.org/de)** \[**choco install languagetool**\]: Grammatik-Prüfung, mächtig, auch für **deutsche Grammatik**
	- Im [Desktop Editor](https://languagetool.org/de/windows) ist das wichtigstes Tastaturkürzel: **Strg+Q** ⭐
	- Auch als [Thunderbird-Extension](https://languagetool.org/de/thunderbird) und damit perfekt für E-Mails ⭐
	- Auch [in Developer-Werkzeuge integriert](https://dev.languagetool.org/software-that-supports-languagetool-as-a-plug-in-or-add-on.html)
	- Auch als Browser-Plugin ([Opera](https://addons.opera.com/de/extensions/details/grammar-and-spell-checker-languagetool/), [Firefox](https://addons.mozilla.org/de/firefox/addon/languagetool/), [Chrome](https://chrome.google.com/webstore/detail/grammar-checker-paraphras/oldceeleldhonbafppcapldpdifcinji), …) und damit perfekt für Overleaf ⭐
	- Auch für LaTeX per VS-Code-Integration per [LTeX-Plugin](https://github.com/valentjn/vscode-ltex)
	- Auch Markdown-Support, bspw. per [Obsidian-Integration](https://github.com/Clemens-E/obsidian-languagetool-plugin)
	- Alternative: **[Duden Mentor](https://www.duden.de/rechtschreibpruefung-online)** (u.a. als [Word Extension](https://appsource.microsoft.com/de-de/product/office/WA200002017)) sowie **[Grammica](https://grammica.com/proofreading)** (ohne Desktop-Integration)
- KI-gestütztes Schreiben:
	- OBACHT: Gilt für eine Abschlussarbeit als High-Tech-Plagiarism [⚡](https://fsymbols.com/signs/hazard/)
	- ChatGPT: [How to Install and Run **ChatGPT** as a Windows App](https://www.makeuseof.com/run-chatgpt-windows-app/)
- **[DeepL](https://www.deepl.com/translator)** \[**choco install deepl**\]: Übersetzungen
	- Wichtigstes Tastaturkürzel: **Strg+C+C** ⭐
- **[QuillBot](https://quillbot.com/)**: Paraphrasierung
	- Auch [als Word Plug-In](https://quillbot.com/word)
- Screenshots: **[Snipaste](https://www.snipaste.com/)** | **[Greenshot](https://getgreenshot.org/)** \[**choco install greenshot**\]
- **[namelix](https://namelix.com/)**: Namensgenerator für Bachel-/Master-/PhD-Projekte, OSS-Projekte, etc.
- Call-for-Paper Termine: **[WikiCFP](http://www.wikicfp.com/cfp/)** | [Computer Science **Conference Search**](https://confsearch.ethz.ch/) (inkl. graphischer Kalender-Funktion)
- Computing Research Conference Rank: [**CORE** Portal](http://portal.core.edu.au/conf-ranks/) | **[GGS](https://scie.lcc.uma.es/)**
- **[SciSpace](https://typeset.io/for-writers/)** (früher: Typeset): Cloud-Editor mit unzähligen [Journal-Vorlagen](https://typeset.io/formats/) für das Schreiben von wissenschaftlichen Publikationen
- Fancy Cloud-/AI-Stuff (€): **[genei](https://www.genei.io/)** sowie [QuillBot-Premium-Features](https://quillbot.com/premium)
- Weiterführende Quelle: [Awesome Thesis](https://github.com/ocean1/awesome-thesis) | [Awesome PhD](https://github.com/macoj/phd) | [PhD Comics](https://phdcomics.com/comics/most_popular.php)

## Anti-Prokrastination

- Druckbare **[Wochenplaner](https://jinxkitchen.de/wp-content/uploads/printables/PDF-printable-jinxkitchen-sprinkle.pdf)** (kostenlos findbar im Dunstkreis [Essens- & Wochenplaner mit Einkaufslisten](https://jinxkitchen.de/printables/))
- Erstellen eines Scrum Burndown-Charts (X: Werktage, Y: Seitenanzahl): [**Burndown-Chart**-Generator (**Printable-HTML**)](https://easyretro.io/tools/burndown-chart-generator/), [**Burndown-Chart**-Generator (**PDF**)](https://www.burndowngenerator.com/)
- Pomodoro: **[Tomato-Timers](https://www.tomatotimers.com/)** (auch für [iOS](https://apps.apple.com/de/app/focus-hub-study-timer/id1478228599)), Android: [Google Play Search](https://play.google.com/store/search?q=pomodoro%20timer&c=apps)
	- Quasi-Pomodoro: **[Boxing-Interval-Timer](https://boxingtimer.org/)** (auch für [Android](https://play.google.com/store/apps/details?id=com.brucemax.boxintervals) und [iOS](https://apps.apple.com/de/app/boxing-timer-professional/id978829173))
	- Physisches Hilfsmittel: (€) **[Zeitwürfel](https://www.amazon.de/gp/product/B079HW6WT7/)**
- Für Fälle in denen Prokrastination in echte Schreibblockaden und ggf. Depressionen übergehen: Die OTH hat eine **[Psychosoziale Beratung](https://www.oth-aw.de/hochschule/ueber-uns/einrichtungen/zentrum-fuer-gender-und-diversity/psychosoziale-beratung/)**
	- Es finden sich auch [Tipps im Netz](https://www.google.com/search?q=prokrastination+schreibblockade+depression)

## Translations

- **[DeepL](https://www.deepl.com/translator)** \[**choco install deepl**\]: Übersetzungen
	- (Unter Windows bspw. mittels chocolatey: )
	- Wichtigstes Tastaturkürzel: **Strg+C+C**
	- Für Entwickler: [**DeepL API** Free](https://www.deepl.com/pro#developer) (5000 chars/month)
- **[OmegaT](https://omegat.org)** \[**choco install omegat**\]: free translation memory tool
- Weiterführende Quelle: [Awesome Translations](https://github.com/mbiesiad/awesome-translations), [Awesome I18N](https://github.com/jpomykala/awesome-i18n)

## Evaluation-Werkzeuge

- Stichprobenumfang-Bestimmung: **[G\*Power](https://www.psychologie.hhu.de/arbeitsgruppen/allgemeine-psychologie-und-arbeitspsychologie/gpower)** \[**choco install gpower**\] aus der Psychologie
- **[LimeSurvey](https://community.limesurvey.org/)**: Umfragen, bspw. für Kundenbefragungen zur Fitness-for-Use
	- Alternativen: [**Tally**.so](https://tally.so/)
- [**SonarQube** Community Edition](https://www.sonarqube.org/downloads/): (Web/Self-Hosted:) Statische Codeanalyse (SCA) für viele Programmiersprachen \[bspw. via **[docker](https://hub.docker.com/_/sonarqube)**\]
	- Cloud-Alternativen: **[DeepSource](https://deepsource.io/)** für viele Programmiersprachen (kostenlos für öffentliche Repos)
	- Desktop-Alternative: **[SourceMeter](https://sourcemeter.com/download)** für gängige Programmiersprachen (**Deep** SCA) | **[Designite](https://www.designite-tools.com/)** für C#/Java (kostenlos für Studierende mittels [Academic License](https://www.designite-tools.com/acad-lic-request/))
- **[Codecov](https://about.codecov.io/for/open-source/)**: Test Code Coverage Analysen, kostenlos für öffentliche Open-Source Repos
- COCOMO (aka Constructive Cost Model):
	- LoC Counting: [cloc](https://github.com/boyter/scc), [scc](https://github.com/boyter/scc)
	- [ProjectCodeMeter](https://www.projectcodemeter.com/cost_estimation/kop1.html)
- **[Google Lighthouse](https://developers.google.com/web/tools/lighthouse/)**: Auch für die rudimentäre Evaluation von PWAs geeignet (Obacht: wissenschaftlich müssen Sie in der Evaluation von PWAs in Ihrer Abschlussarbeit tiefer bohren, aber den Lighthouse-Test sollten Sie auf jeden Fall auch bestehen)
- Website Accessibility Checker:
	- Cloud: (EN:) [web accessibility evaluation tool (**WAVE**)](https://wave.webaim.org/) ⭐ | (DE:) [buchstaben.com **Barrierefreiheit Test**](https://www.buchstaben.com/barrierefreiheit-test) ⭐, [experte.de Barrierefreiheit Test](https://www.experte.de/barrierefreiheit)
		- Spezialthema Barrierefreie **Farben**: [Accessible Colors](https://accessible-colors.com/) (man muss seine Vorder- und Hintergrundfarbe manuell eintragen)
		- Mittlerweile Kommerziell (€): [TPG ARC Scan](https://www.tpgi.com/free-website-accessibility-scan/) (formerly: Cynthia Says)
		- Barrierefreiheit ist mittlerweile auch Teilaspekt von [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/)
	- Browser Add-In: **[Axe](https://www.deque.com/axe/)**, **[WAVE](https://wave.webaim.org/extension)**, [Siteimprove](https://addons.mozilla.org/firefox/addon/si-accessibility-checker/)
- User tracking and analysis: **[Amplitude](https://amplitude.com/)**

## Management & Agile Methoden

- Terminumfragen: **[nuudel](https://nuudel.digitalcourage.de/)** ⭐, [fragab](https://fragab.com/)
- Kalenderwoche: [aktuelle-**kalenderwoche**.org](https://www.aktuelle-kalenderwoche.org/)
- Zeitzonen: **[worldtimebuddy](https://www.worldtimebuddy.com/)**, [Time Zone Map](https://www.timeanddate.com/time/map/)
- Ganttcharts:
	- Desktop: FOSS [Agantty](https://www.agantty.com/)
	- Web: [Agantty](https://www.agantty.com/), [team gantt](https://www.teamgantt.com/), [toggl plan](https://toggl.com/plan/)
- Kanban-Board: **[Wekan](https://wekan.GitHub.io/)** «Self-hosted»
- Timer: **[Boxing Interval Timer](https://boxingtimer.org/)** oder [Online-Stopwatch](https://www.online-stopwatch.com/timer/5minutes/) (5min) etc. pp.
- Time Tracking? **[TopTracker](https://www.toptal.com/tracker)**
- Work Management? **[monday.com](https://monday.com/)** (free: 2 Persons, 3 Boards)
- Projektmanagement? **[OpenProject](https://www.openproject.org/)** \[via [Docker](https://www.openproject.org/docs/installation-and-operations/installation/docker/)\] | **[GitLab](https://about.gitlab.com/install/)**[Issue Tracking](https://about.gitlab.com/stages-devops-lifecycle/issueboard/) \[bspw. via [Docker](https://docs.gitlab.com/ee/install/docker.html) oder per [Cloud](https://about.gitlab.com/pricing/)\] | Cloud: **[Taiga.io](https://www.taiga.io/)**
- Mind Mapping? Desktop: **[XMind](https://www.xmind.net/)** \[**choco install xmind**\] | **[PlantUML MindMaps](https://plantuml.com/mindmap-diagram)** | **[Mermaid](https://mermaid.js.org/syntax/mindmap.html)**
- Whiteboard? **[OpenBoard](https://openboard.ch)** \[**choco install openboard**\]
- Zufallsentscheidung? [Online-**Glücksrad**](https://de.piliapp.com/random/wheel/) | **[Spin the Wheel](https://spinthewheel.io/de)**
- Produktmanagement: **[pendo](https://www.pendo.io/)** kostenlos für 1 Web+Mobile App mit bis zu 1000 Endnutzern
- Spreadsheets-on-Steroids: Cloud-basiertes **[Airtable](https://www.airtable.com/)** (vereinigt Aufgabenlisten, Projektmanagement, Spreadsheets, etc.)
- Agile Retrospektiven: Methodenauswahl per **[Retromat](https://retromat.org/de/)** sowie **[Random Retros](https://www.randomretros.com/)**
- (zzgl. der anschließende Abschnitt: [Kollaborative Werkzeuge](#kollaborative-werkzeuge))
- Weiterführende Quellen: [Awesome Agile](https://lorabv.GitHub.io/awesome-agile/)

## Kollaborative Werkzeuge

- Kollaboratives **Whiteboarding** (inkl. Zeichnen): **[invision](https://www.invisionapp.com/)** | **[miro](https://miro.com/de/)** | **[mural](https://start.mural.co/)**
- Kollaborative **Text**-Bearbeitung?
	- No Sign-Up: **[YoPad](https://yopad.eu)** | **[EduPad](https://edupad.ch)**
	- With Sign-Up: [Bit.ai](https://bit.ai/) | [Google Docs](https://docs.google.com/document/u/0/) | [Word Online](https://office.live.com/start/word.aspx) | [OnlyOffice Personal](https://personal.onlyoffice.com/)
- Kollaborative **Spreadsheet**-Bearbeitung?
	- No Sign-Up: **[EtherCalc](https://ethercalc.net)**
	- With Sign-Up: [Google Sheets](https://sheets.google.com/document/u/0/) | [Excel Online](http://office.live.com/start/Excel.aspx) | [OnlyOffice Personal](https://personal.onlyoffice.com/)
- Kollaborative **Präsentationen**? **[Pitch](https://pitch.com/)**
- Kollaboratives **Mind Mapping**: **[ClickUp](https://clickup.com/features#view-tab-mind-maps)**
- Kollaborativer **Software-Entwurf/Modellierung**: [**draw.io**/**diagrams.net** over Google Drive](https://www.drawio.com/doc/faq/share-diagrams), [**Visual Paradigm** Online](https://online.visual-paradigm.com/pricing/)
	- ([LucidChart](https://www.lucidchart.com/), aber nur 3 Dokumente kostenlos)
	- (€€€: [Cloudcraft](https://www.cloudcraft.co) unterstützt Kollaborative Modellierung, allerdings nur in den teuren Varianten)
- Kollaboratives **Medien-Design**: **[snappa](https://snappa.com/)**
- Kollaboratives **Malen**: **[Aggie.io](https://aggie.io/)**
- Kollaborative **Feedback für Medien/Designs**: **[cage](https://www.cageapp.com/)**
- Kollaborative **Aufgabenliste**: **[Trello](https://trello.com/)**
- Kollaboratives **Projektmanagement**: **[Taiga.io](https://www.taiga.io/)**, [**GitLab** Issue Tracking](https://about.gitlab.com/pricing/)
- **[worldbuddy](https://www.worldtimebuddy.com/)**: Time Converter and World Clock
- **[aktuelle-kalenderwoche.org](https://www.aktuelle-kalenderwoche.org/)**: Planen und Nachschlagen

## Zeichnen

- Upscaler/Upsampling: (kann ggf. auch Kompressionsartefakte entfernen)
	- Web/Cloud: [bigjpg](https://bigjpg.com), [Nero AI](https://ai.nero.com), [imglarger](https://imglarger.com), [Gigapixel AI](https://www.topazlabs.com/gigapixel-ai-it-really-works), [Waifu2X](https://waifu2x.io/), etc. pp.
	- Desktop: [Upscayl](https://upscayl.github.io) ⭐ (choco install upscayl)
- Bild-Vektorisierer (Image to SVG):
	- Web/Cloud: [vectorizer.io](https://de.vectorizer.io), [Aspose](https://products.aspose.app/svg/de/image-vectorization), [convertio.co](https://convertio.co/de/image-converter/)
	- Desktop: [inkscape](https://inkscape-manuals.readthedocs.io/en/latest/tracing-an-image.html) (allows for color by quantization and multiple scanning; based on famous but black/white [potrace](https://potrace.sourceforge.net))
- Hintergrund-Entferner:
	- Web/Cloud: [PhotoRoom](https://www.photoroom.com/hintergrund-entfernen), [Erase.bg](https://www.erase.bg/de), [cutout.pro](https://www.cutout.pro/remove-background)
	- Desktop: [rembg](https://github.com/danielgatis/rembg) ⭐ (pip install rembg, pip install "rembg[cli]"; basiert auf [ONNX Runtime](https://onnxruntime.ai))
- Microsoft **PowerPoint**: Unterschätzen Sie PowerPoint nicht als universelles Zeichenwerkzeug!
	- Es ist ebenfalls mein Lieblingswerkzeug für Poster (DIN A1).
	- Man kann in PowerPoint sogar Wireframing betreiben, mittels [Keynotopia](https://keynotopia.com/).
	- Microsoft Office 365 Pro ist [kostenlos über studisoft.de](https://www.studisoft.de/shibboleth/shibdwayf?vi=23) für Studierende der OTH-AW
- Microsoft **Visio**: Ein Klassiker. Kommerziell. Eine Desktop-Anwendung. Mittlerweile durch draw.io ersetzbar.
	- Es gibt eine [Visio Stencils Datei für E/R-Modellierung und erweiterte E/R-Modellierung](http://www.cyberlytics.eu/theses/templates/ERD-Chen76_EERD-ElmasriNavathe94.vss) aus meiner eigenen Feder
	- Derzeit ist Visio mutmaßlich nicht in der Microsoft Office 365 Pro Variante enthalten, die Sie kostenlos über studisoft.de beziehen können; aber Visio ist Teil der [Microsoft Azure Dev Tools for Teaching](https://www.oth-aw.de/hochschule/services/online-services/downloads-software/), welche für Studierende ebenfalls kostenlos zur Verfügung stehen
- Adobe **Illustrator**: Für ambitionierte Vektorgrafiken.
	- Illustrator erlaubt das Öffnen von PDFs und eignet sich dadurch gut zur Extraktion von Grafiken, ggf. in hochauflösendem Vektorformat.
	- Über die Zugehörigkeit zur OTH-AW müssten Sie auch einen Zugang zur Adobe Creative Cloud bekommen können
- [**draw.io**/diagrams.net](https://app.diagrams.net) ⭐: Universelles Zeichenwerkzeug, u.a. auf Augenhöhe mit Microsoft Visio
	- Unterstützt ebenfalls Notationen wie UML und E/R-Diagramme
	- Entweder als Cloud-WebApp oder als Desktop-Anwendung
	- (Unter Windows bspw. mittels chocolatey: **choco install drawio**)
- Datenvisualisierung
	- **[Flourish](https://flourish.studio/)** ⭐: Univerelle Datenvisualisierung, besser als Microsoft Excel ([Templates](https://app.flourish.studio/templates))
	- **[RAWGraphs](https://www.rawgraphs.io/)** ⭐: Open Source Datenvisualisierung, u.a. auf Augenhöhe mit Microsoft Excel ([Templates](https://www.rawgraphs.io/learning#charts-and-templates)
- **[Krita](https://krita.org/)** ⭐: Open Source Alternative für Photoshop, also für Rastergrafiken
	- (Unter Windos bspw. mittels chocolatey: **choco install krita**)
	- \[ Es gibt andere Open Source Rastergrafikwerkzeuge, aber um Himmels willen **nicht** Gimp… \]
- Themenkomplex: Isometrische 3D Vector Graphics/Icons
	- Einstieg: [Referenz-Google-Suche](https://www.google.de/search?q=awesome+isometric+vector+3d)
		- Außerdem sind isometrische Icons für eine [konzeptionelle SW-Architektur in **Visio**](https://surrogate-tm.GitHub.io/mailant/2004/11/21/great-shapes-for-conceptual-architecture-diagrams-in-visio-part-1.htm) enthalten
	- Werkzeuge:
		- **[Affinity Designer](https://affinity.serif.com/)** (vgl. [YouTube-Tutorial-Video](https://m.youtube.com/watch?v=oxm9VAMN3Dk)) als generisches Werkzeug mit spezieller Isometric-3D-Unterstützung
		- **[Cloudcraft](https://www.cloudcraft.co)** zur Visualisierung von Cloud-Architekturen ([Beispiele](https://www.google.com/search?q=cloud+architecture+cloudcraft&tbm=isch))
		- **[Icograms](https://icograms.com/)**

## Presentations

- **PowerPoint** (kostenlos für OTH-Studierende) oder dessen **kostenlose Desktop- oder HTML-Alternativen** (s. unten)
	- Webseiten live in PPT-Präsentation einbinden?
		- Derzeit praktisch nicht mehr machbar. Es gibt nur noch [ClassPoint](https://www.classpoint.io/features/embedded-browser) als Work-Around.
		- ([PollEveryWhere](https://www.polleverywhere.com/) hatte die LiveSlides-Funktion integriert aber hat sie derzeit wieder verloren.)
		- ([LiveSlide](https://liveslides.software.informer.com/download/) war der Vorgänger von PollEverywhere und wurde in PollEv integriert und ist jetzt installierbar aber unbrauchbar.)
		- (Die Powerpoint-Extension von Microsoft selbst namens Web-Viewer war leider schon immer fast unbrauchbar.)
	- Man kann auch mittels PowerPoint selbst eine Bild-in-Bild [Video-Aufzeichnung](https://insider.office.com/de-de/blog/tell-your-story-with-video-recording-in-powerpoint) („Teleprompter“) seiner Präsentation machen
	- Dateigröße von PPT-Päsentation
		- Eingebaute [**compress pictures** Funktion](https://support.microsoft.com/de-de/office/verringern-der-dateigr%C3%B6%C3%9Fe-ihrer-powerpoint-pr%C3%A4sentationen-9548ffd4-d853-41e7-8e40-b606bca036b4) ⚠️
		- neuxpower ⭐
			- Dateigröße tiefgehend analysieren (und manuell fixen)? neuxpower [Slidewise](https://neuxpower.com/slidewise-powerpoint-add-in) Extension (mit einer wertvollen Free Version ⭐ und einer noch wertvolleren (€) Bezahlversion)
			- Dateigrößen automatisch fixen? (€) neuxpower [NXPowerLite](https://neuxpower.com/nxpowerlite-desktop) ⭐ (für PPT, aber auch Word, Excel und PDFs)
				- Obacht mit den drei vorgefertigten Profilen [Balanced/Strong/Basic](https://support.neuxpower.com/hc/en-us/articles/201046011-How-do-Optimize-profile-optimization-settings-affect-my-files): Keines passt m.E. so richtig und ich würde ein customized profile empfehlen:
					| Option | Wert |
					| -------- | -------- |
					| Resize images for display at: | 1920 x 1080 (1080p) |
					| Allow JPEG conversion	| Enabled |
					| Remove embedded Excel data from charts (PowerPoint & Word) | Disabled |
					| Reduce color depth of PNG images (Office) | Enabled |
					| Maintain compatibility with Word 2007 (Word) | Disabled |
					| JPEG Quality (JPEG) | 8 |
					| Remove Exif Data | Enabled |
			- Alle drei Varianten (compress pictures, Slidewise, NXPowerLite) und mehr wertvolle Hinweise werden beschrieben im Webartikel [Reduce **PPT file size**](https://neuxpower.com/blog/why-is-my-powerpoint-so-big-and-how-can-i-reduce-the-size-of-the-ppt) ⭐
			- Kostenloser Online-Datei-Compressor von neuxpower = WeCompress: [Analyzer](https://www.wecompress.com/en/analyze) (max. 200MB) und [Compressor](https://www.wecompress.com/en/) (max. 50MB)
- **[latex-beamer](https://ctan.org/pkg/beamer)**
	- Auch in [Overleaf](https://www.overleaf.com/learn/latex/Beamer) integriert
	- (Eine [OTH-Vorlage für beamer](https://www.oth-aw.de/latex/) findet sich in unserem GitLab)
	- Nennenswert: [Adobe PDF to PPT](https://www.adobe.com/acrobat/online/pdf-to-ppt.html) (use in private tab for reset)
- HTML Presentation Frameworks
	- **[reveal.js](https://revealjs.com/)** ⭐ | [shower](https://github.com/shower/shower) with [CLI](https://github.com/shower/cli/)
	- (Inaktiv: [impress.js](https://github.com/impress/impress.js) | [Inspire.js](https://github.com/LeaVerou/inspire.js) | [deck.js](https://github.com/imakewebthings/deck.js) | [DZSlides](https://github.com/paulrouget/dzslides) | uvm.)
- Markdown Presentation Frameworks
	- Markdown to HTML Slide Decks
		- **[Slidev](https://github.com/slidevjs/slidev)** ⭐ (local [slidev-cli](https://sli.dev/builtin/cli#export) bzw. [Cloud-App](https://sli.dev/)) | [Decker](https://elearning.uni-wuerzburg.de/decker/) | [Marp](https://marp.app/) ([mapr-cli](https://github.com/marp-team/marp-cli))
		- Nennenswert: [reveal.js](https://revealjs.com/) unterstützt ebenfalls Markdown
	- Markdown to PDF Slide Decks
		- [typst](https://typst.app/) mit **[touying](https://touying-typ.github.io/)** ⭐
			- Das `typst compile` für einen Foliensatz ist im Bereich Millisekunden und daher im Round-Trip einem latex-beamer deutlich überlegen!
			- Optisch ist touying mit latex-beamer vergleichbar und als direkter Ersatz ausgelegt.
			- OBACHT: genau genommen ist die typst Syntax eine Mischung aus AsciiDoc und Markdown (bspw. MarkDown: Code-Blöcke und Listen | AsciiDoc: Überschriften sowie bold und italics)
		- [Quarto](https://quarto.org/docs/output-formats/all-formats.html) unterstützt [Presentations](https://quarto.org/docs/presentations/)
	- Markdown to PPTX Slide Decks
		- Local/CLI:
			- Experimentelle Option per [Marp](https://github.com/marp-team/marp-cli): `marp --pptx --pptx-editable slide-deck.md`
			- Option per [Quarto](https://quarto.org/docs/presentations/powerpoint.html): `quarto render slide-deck.qmd --to pptx --reference-doc template.pptx`
		- Cloud: [Gamma](https://gamma.app/) (Skizze: Import von Markdown möglich und Export von PPTX möglich)

**Nennenswerte Hilfswerkzeuge**:

- **[pdfsizeopt](https://github.com/pts/pdfsizeopt)**: optimize the size of PDF files (with focus on PDFs created from TeX and LaTeX documents)
- **[DirectPoll](https://directpoll.com)**: Abstimmungssystem („Clicker“), also Umfragen und Votings bei Großgruppen
	- Alternativen bei Großgruppen:
		- Cloud: **[OnlineTED](https://onlineted.de/)** Basic (max. 100 Teilnehmer) | **[Tweedback](https://tweedback.de/)** Free (nur 24h Session-Dauer) | **[Mentimeter](https://www.mentimeter.com)** (max. 2 Fragen pro Präsentation) | [**vevox**.com](https://www.vevox.com/pricing/education-pricing) (Multiple-Choice-Fragen kostenlos; früher meetoo.io)
		- Self-Hosted: **[Arsnova](https://gitlab.com/particify/dev/foss/arsnova)** bzw. Particify \[via [Docker](https://gitlab.com/particify/dev/foss/docker-orchestration)\]
		- Desktop: **[FreeQuizDome](https://www.freequizdome.com/)**
	- Alternativen für kleinere Gruppen: **[PollEveryWhere](https://www.polleverywhere.com/)** Intro (max. 25 Teilnehmer, aber PPT-Integration) \[**choco install polleverywhere**\] | **[Kahoot!](https://kahoot.com/register/kahoot-study-pricing/)** (max. 10 Teilnehmer) | **[AhaSlides](https://ahaslides.com/pricing/)** (max. 7 Teilnehmer; mit [PowerPoint-Extension](https://ahaslides.com/blog/extension-for-powerpoint/))
	- Beispielfragen: [90 Mentimenter-Beispiele](https://www.mentimeter.com/de-DE/blog/awesome-presentations/85-poll-questions-for-every-occasion)
- Videos für eine Präsentation beschleunigen oder verlangsamen: [Online Video Cutter » Change Video Speed](https://online-video-cutter.com/change-video-speed)

## Poster

\[Hier: Scientific Research Posters\]

- Formate:
	- DIN A1: 59,4 cm x 84,1 cm
		- Poster-Print 3:4-Format: 60 cm x 80 cm
		- Poster-Print 2:3-Format: 60 cm x 90 cm
	- DIN A0: 84,1 cm x 118,9 cm
		- Poster-Print 2:3-Format: 80 cm x 120 cm
		- Poster-Print 3:4-Format: 90 cm x 120 cm
- **PowerPoint**: SmartTab "Entwurf" » Foliengröße » Benutzerdefiniert
	- PowerPoint sollte als Werkzeug zur Poster-Gestaltung durch Laien nicht unterschätzt werden!
- [typst](https://typst.app/universe/search/?category=poster) mit **[Peace of Posters (PoP)](https://jonaspleyer.github.io/peace-of-posters/showcase/)**
- [latex](https://www.overleaf.com/learn/latex/Posters) mit **[beamerposter](https://www.ctan.org/pkg/beamerposter)**  sowie ggf. [tikzposter](https://ctan.org/pkg/tikzposter) oder [baposter](https://github.com/mloesch/baposter)
	- Nennenswerte weitere Alternative: Poster auch mit **[tcolorbox](https://ctan.org/pkg/tcolorbox)** ⭐ welches ebenfalls [für Poster geeignet](https://mirrors.ctan.org/macros/latex/contrib/tcolorbox/tcolorbox-tutorial-poster.pdf) ist!
- [Canva](https://www.canva.com/create/posters/), auch für [Scientific Posters](https://www.canva.com/posters/templates/research/)

## Plug-Ins / Add-Ins / Extensions

- Microsoft Office
	- **PowerPoint** Add-Ins: bspw. [iSpring **PPT-Add-Ins-Empfehlung**sliste](https://www.ispringsolutions.com/blog/boost-your-powerpoint-7-free-powerpoint-add-ins)
	- **Excel** Add-Ins: bspw [Power-User **Excel-Add-Ins-Empfehlung**sliste](https://www.powerusersoftwares.com/post/75-best-add-ins-plugins-and-apps-for-excel-free)
	- **Outlook** Add-Ins: bspw [mxHERO **Outlook-Add-Ins-Empfehlung**sliste](https://www.mxhero.com/51-best-outlook-email-add-ins)
	- **Word** Extensions: bspw [Power-User **Word-Extensions-Empfehlung**sliste](https://www.powerusersoftwares.com/post/2016/08/14/40-of-the-best-add-ins-plugins-and-apps-for-microsoft-word-free-or-not)
	- **VBA** Entwickler-Werkzeuge: bspw. [xtrail **VBA-Add-Ins-Empfehlung**sliste](https://www.xltrail.com/blog/developer-tools-for-microsoft-excel) mit [Rubberduck](https://github.com/retailcoder/Rubberduck) \[**choco install rubberduck**\]
- Adobe
	- **Photoshop** Plug-Ins: bspw. [skylum **Photoshop-Plug-Ins-Empfehlung**lsliste](https://skylum.com/de/blog/best-free-photoshop-plugins-to-improve-your-creative-work)
	- …
- Software-Programming
	- **VS Code** Extensions: **[Open VSX Registry](https://open-vsx.org/)** | **[Marketplace](https://marketplace.visualstudio.com/VSCode)** sowie bspw. [hackr.io **Code-Extensions-Empfehlung**sliste](https://hackr.io/blog/best-vscode-extensions)
	- **Visual Studio** Extensions: **[Marketplace](https://marketplace.visualstudio.com/)** sowie bspw. [elmah.io **Visual-Studio-Extensions-Empfehlung**sliste](https://blog.elmah.io/list-of-the-best-free-visual-studio-extensions/)
	- **Eclipse IDE** Plug-Ins: **[Marketplace](https://marketplace.eclipse.org/category/free-tagging/java)** sowie bspw. [tabnine **Eclipse-Plug-Ins-Empfehlung**sliste](https://www.tabnine.com/blog/plugins-for-eclipse/) bzw. [snyk-Liste](https://snyk.io/blog/10-eclipse-plugins-you-shouldnt-code-without/)
	- …

## Bildmaterialien

- Kostenlos/lizenzfreundlich:
	- Emojis: **[Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)**, **[Emoji Finder](https://emoji.muan.co/)**
	- **Concepts**/Nouns: **[Noun Project](https://thenounproject.com/)** ⭐ (Absolutely awesome! Free of charge with attributions, but account required.)
	- **Fotos/Bilder:** **[Unsplash](https://unsplash.com/de)**, **[pixabay](https://pixabay.com/)** ⭐
		- Weitere: [Pexels](https://www.pexels.com/)
	- **Illustrationen:** **[unDraw](https://undraw.co/)** ⭐
		- Weitere: [clker](http://www.clker.com), [pixabay](https://pixabay.com/vectors/) (mit Filter auf „Vectors“)
	- **Icons:** **[Noun Project](https://thenounproject.com/)** ⭐, **[iconmonstr](https://iconmonstr.com)**, [**Feather** (OSS)](https://feathericons.com), [**FontAwesome** (Freebies)](https://fontawesome.com/v6/search?o=r&m=free), **[Emojis](https://www.webfx.com/tools/emoji-cheat-sheet/)**, **[CryptoKit](https://cryptokit.ch/specimen)**
		- Cloud Computing: [**Kubernetes** Icons Set](https://github.com/kubernetes/community/tree/master/icons)
		- Weitere: [Line Awesome](https://icons8.com/line-awesome), [Academicons](https://jpswalsh.GitHub.io/academicons/), [Twemoji](https://ellekasai.GitHub.io/twemoji-awesome/), [Font Mfizz](http://fizzed.com/oss/font-mfizz), [Google Font Icons](https://fonts.google.com/icons), [Material Design Icons](https://pictogrammers.com/library/mdi/), [Bootstrap Icons](https://icons.getbootstrap.com), [css.gg](https://css.gg/app), [Boxicons](https://boxicons.com), [Font Awesome Extension](https://andrelzgava.GitHub.io/font-awesome-extension/), [Streamline Freebies](https://www.streamlinehq.com/freebies))([Iconify Free Icons](https://freebiesbug.com/illustrator-freebies/iconify-650-free-icons/))
	- **[Free Fonts](https://speckyboy.com/best-free-fonts/)**: Kostenlose Schriftarten
	- Kunst, Kultur, Geschichte: **[Prometheus-Bildarchiv](https://www.prometheus-bildarchiv.de/)**
- AI-rendered Illustrations/Art:
	- Prompt Galleries (Prompts und deren AI-generierten Bilder): **[PromptHero](https://prompthero.com/)**, **[Playground AI](https://playgroundai.com/)**
	- Unterstützung bei der Prompt Generation: **[NightCafe](https://nightcafe.studio/)**, **[promptoMANIA](https://promptomania.com/prompt-builder/)**
	- Von Unternehmen mit Marktführerschaften: [**Adobe** Firefly](https://firefly.adobe.com/), [**Microsoft** Designer](https://designer.microsoft.com/), ([**Google** Imagen](https://imagen.research.google/) in Vorbereitung)
	- (vgl. auch die Lernmaterialien zu [Prompt Engineering](https://github.com/cyberlytics/awesome-basics#ai))
	- Open Source: **[OpenArt](https://openart.ai/create)** ⭐ ([github](https://github.com/OpenArt-AI)), **[Stable Diffusion](https://huggingface.co/spaces/stabilityai/stable-diffusion)** als free cloud UI via Huggingface Space (eigentliches [KI-Modell](https://github.com/CompVis/stable-diffusion) auf GitHub) by [stability.ai](https://stability.ai/) + [runway](https://runwayml.com/) sowie darauf basierend **[Lexica](https://lexica.art/)**
		- Kommandozeilenwerkzeug: **[imaginAIry](https://github.com/brycedrennan/imaginAIry)**
	- Closed Source: **[craiyon](https://www.craiyon.com/)** (früher: „DALL·E mini“), per Warteliste: [OpenAI DALL·E 2](https://labs.openai.com/waitlist)
		- (€:) **[Midjourney](https://www.midjourney.com/)** ([Anleitung](https://docs.midjourney.com/docs/midjourney-discord); benötigt [Discord](https://discord.com/download); [Pricing](https://docs.midjourney.com/docs/plans))
	- Other: **[artbreeder](https://www.artbreeder.com/)** (formerly known as GANbreeder), **[Lensa](https://play.google.com/store/apps/details?id=com.lensa.app)** (u.a. für AI-Avatare)
	- Stark limitierte kostenlose Angebote: [stockimg.ai](https://stockimg.ai/), [runway](https://runwayml.com/)
	- Disclaimer: [Rule 34](https://en.wikipedia.org/wiki/Rule_34) zzgl. Kürzelkunde [NSFW](https://en.wikipedia.org/wiki/Not_safe_for_work)
	- Weiterführende Quellen: [TopAi.tools](https://topai.tools/) | [Prompt-Werkzeug-Liste auf reddit](https://www.reddit.com/r/StableDiffusion/comments/xcrm4d/useful_prompt_engineering_tools_and_resources/)

## Mathe

- **[MathCha.io](https://www.mathcha.io)**: Eine Cloud-WebApp zum zeichnen von mathematischen Grafiken
	- Erlaubt den Export nach SVG und sogar nach Tikz zwecks Latex
- **[Geogebra](https://moodle.oth-aw.de/mod/url/view.php?id=86125)**: Graphikrechner, 2D Geometrie, 3D Geometrie, Algebra-Rechner, …
	- (Auch als Desktop-App unter Windows verfügbar, bspw. mittels chocolatey: **choco install geogebra6** bzw. **choco install geogebra-geometry**)
	- Alternative: **Desmos** ([Desmos Calculator](https://moodle.oth-aw.de/mod/url/view.php?id=86074), [Desmos Geometry](https://moodle.oth-aw.de/mod/url/view.php?id=86075))
- **[JSXGraph](https://jsxgraph.uni-bayreuth.de)**: JavaScript library for cross-browser interactive geometry, function plotting, charting, and data visualization
- siehe auch Abschnitt **[Data Science](https://github.com/cyberlytics/awesome-bdccai-tools#data-science)** auf der Schwester-Seite zu BDCC/AI
- siehe unten bei [Kostenlose Alternativen](#kostenlose-alternativen) zu SAS, MathWorks Matlab und Wolfram Mathematica

## Job-Bewerbungen

\[ Parallel zur Abschlussarbeit werden Sie mit der Jobsuche und Ihren Bewerbungen beginnen. \]

- Biometrisches Passbild Generator: [photoaid.com](https://photoaid.com/de-de/biometrisches-passbild)
- Weitere Tipps: vgl. [Digitaler-Ressourcenpool-Schwesterseite](https://github.com/cyberlytics/awesome-basics#bsc-bonusliste)
- Lebenslauf-Werkzeuge für Informatiker:
	- LaTeX: **[CV-Templates](https://de.overleaf.com/latex/templates/tagged/cv)** (mein eigenes Paket: [ECV](https://ctan.org/pkg/ecv))
	- Web: [Free **Responsive HTML5 Website Template**](https://www.google.de/search?q=Free+Responsive+HTML5+Website+Template)
	- Entwickler-CV: **[JSON resume](https://jsonresume.org/)**
	- Cloud Resume Builder: bspw. [CakeResum](https://www.cakeresume.com/), [zety](https://zety.com/), [Resume Genius](https://resumegenius.com/), uvm.
- KI-gestütztes Bewerbungsbild: [AI Portrait](https://www.aiportrait.me/)

## Kostenlose Alternativen

- Adobe **Photoshop**
	- Desktop: **[Krita](https://krita.org/)** \[**choco install krita**\] + **[RawTherapee](https://www.rawtherapee.com/)** for RAW files \[**choco install rawtherapee**\]
	- Cloud: **[Pixlr](https://pixlr.com/de/)**
	- AI-gestützte Teilaspekte: [clipdrop.co](https://clipdrop.co/), [iLoveIMG](https://www.iloveimg.com/)
	- Kollaboratives Malen: **[Aggie.io](https://aggie.io/)**
- Adobe **Illustrator** (und Adobe Fresco)
	- Desktop: **[FireAlpaca](https://firealpaca.com/)** \[**choco install firealpaca**\] | **[Inkscape](https://inkscape.org/)** \[**choco install inkscape**\]
	- Cloud: **[Vectr](https://vectr.com/)** | **[Canva](https://www.canva.com)** | [Graphite](https://editor.graphite.rs/) | [Corel Vector](https://app.corelvector.com/) (formerly: Gravit Designer)
	- Kollaboratives Zeichnen (Design): **[snappa](https://snappa.com/)**
	- Kollaboratives Zeichnen (Whiteboarding): **[invision](https://www.invisionapp.com/)** | **[miro](https://miro.com/de/)** | **[mural](https://start.mural.co/)**
- Adobe **InDesign**
	- Desktop: **[Scribus](https://www.scribus.net/)** \[**choco install scribus**\]
	- Cloud: **[LucidPress](https://www.lucidpress.com/)** | **[Canva](https://www.canva.com)**
- Adobe **Acrobat** Pro
	- Desktop:
		- PDF-Editor: **[PDF-XChange Editor](https://pdf-xchange.eu/pdf-xchange-editor/)** \[**choco install pdfxchangeeditor**\]
		- Toolbox: **[CubePDF Utility](https://www.cube-soft.com/cubepdfutility/)** ⭐, [iLovePDF Desktop](https://www.ilovepdf.com/desktop), or [PDF24 Creator](https://tools.pdf24.org/creator)
		- PDF-Compressor: (€) neuxpower [NXPowerLite](https://neuxpower.com/nxpowerlite-desktop) (Top!), kostenlos [iLovePDF Desktop](https://www.ilovepdf.com/desktop)
		- PDF-Conversion to PowerPoint: only Acrobat itself, other Desktop/CLI approaches are garbage, but there are free Online alternatives below
	- Web:
		- PDF-Editor: [Sejda](https://www.sejda.com/pdf-editor), [iLovePDF Editor](https://www.ilovepdf.com/edit-pdf) or [PDFescape](https://www.pdfescape.com/)
		- Toolbox: [iLovePDF](https://www.ilovepdf.com/), [PDF24 Tools](https://tools.pdf24.org/), [Smallpdf](https://smallpdf.com/pdf-tools), or [pdfforge Online](https://www.pdfforge.org/online/)
		- PDF-Compressor: neuxpower [wecompress](https://www.wecompress.com/) (max. 50MB), [iLovePDF Compress](https://www.ilovepdf.com/compress_pdf)
		- PDF-Conversion to PowerPoint: Adobe Online Tool **[Acrobat PDF to PPT](https://www.adobe.com/acrobat/online/pdf-to-ppt.html)** ⭐ (use in private tab for reset), (I have not tried, yet: [iLovePDF pdf-to-powerpoint](https://www.ilovepdf.com/pdf_to_powerpoint), [Smallpdf pdf-to-ppt](https://smallpdf.com/pdf-to-ppt) or [PDF24 pdf-to-powerpoint](https://tools.pdf24.org/pdf-to-powerpoint))
- Prepress Tooling: Adobe **[Preflight](https://helpx.adobe.com/acrobat/using/analyzing-documents-preflight-tool-acrobat.html)**, Callas **[pdfToolbox](https://www.callassoftware.com/en/products/pdftoolbox/pdftoolboxdesktop)**/[pdfaPilot](https://www.callassoftware.com/en/products/pdfapilot/pdfapilotdesktop) and Enfocus **[PitStop](https://www.enfocus.com/pitstop-pro)**
	- Desktop:
		- In general: No free alternative, but a mix of [GhostScript](https://www.ghostscript.com/releases/gsdnld.html) (Win: use gswin64c.exe; i.a., ps2pdf, pdf2ps), [pdftk free](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) (concat files, add security, compress), [Xpdf](https://www.xpdfreader.com/download.html) (pdftops, pdftotext, pdftohtml, pdftoppm, pdftopng, pdfimages, pdfinfo, pdfdetach,pdftops), [poppler](https://community.chocolatey.org/packages/poppler) (i.a., pdffonts), and Apache [PDFBox](https://pdfbox.apache.org/) as well as optionally [PsUtils](https://gnuwin32.sourceforge.net/packages/psutils.htm) (i.a., psnup, psbook)
		- PDF/X-1a: **[scribus](https://www.scribus.net/)** \[**choco install scribus**\]
			- Open arbitrary PDF file in Scribus (use default option **text as vectors**)
			- Use **File** » **Document Setup...** » **Color Management**:
				- Select **Activate Color Management**
				- Optional: Download, e.g., CoatedFOGRA39.icc and save it alongside the PDF! Then you can change, in the Color Management dialog, the color profiles to the alongside icc file profile, e.g., using CoatedFOGRA39 for all CMYK options (and just keep sRGB for the RGB options)
			- Use **File** » **Export** » **Save as PDF...**:
				- In General tab: select **PDF/X-1a** as output compatibility standard
				- In Fonts tab: select **Outline All Fonts**
	- Cloud:
		- In general: No free alternative.
		- PDF/X-1a: **[pdfrest](https://pdfrest.com/apitools/convert-to-pdfx/)** (Starter account with free contingent)
- Apple **Photos** / Google **Picasa**:
	- (Category: Photo Cataloging, Image Organizer, Metadata Manager)
	- Desktop: **[Mylio Photos](https://mylio.com/download/)** (free personal Ed.), [Tonfotos](https://tonfotos.com/)
		- Viewer-centric: **[FastStone Image Viewer](https://www.faststone.org/)** ⭐ \[**choco install fsviewer**\] | [ACDsee Free](https://www.acdsee.com/en/products/acdsee-free/)
	- Web/Self-Hosted: [Piwigo](https://piwigo.org/), [PhotoPrism](https://www.photoprism.app/)
	- Cloud: iPhoto, Google Photos, …
- Adobe **LightRoom**
	- (Category: Non-Destructive RAW Photo Editor and Photography Workflows aka Lightweight DAM)
	- Desktop: **[DarkTable](https://www.darktable.org/)** \[**choco install darktable**\] 
		- zzgl. die DAM-Alternative unten!
		- Editor-only: **[RawTherapee](https://www.rawtherapee.com/)** \[**choco install rawtherapee**\]
	- Cloud: **[polarr](https://photoeditor.polarr.co/)**
- Adobe **Experience Manager** bzw. **MediaValet**
	- (Category: Media Asset Management bzw. Digital Asset Management = DAM)
	- Desktop: **[digiKam](https://www.digikam.org/)**
	- Web/Self-Hosted: **[AtroDAM](https://www.atrodam.com/)**, **[Phraseanet](https://www.phraseanet.com/)**
	- Cloud: **[ResourceSpace](https://www.resourcespace.com/free)** (free 10GB), [Razuna](https://razuna.com/pricing/)
		- (Cloud-Kommerziell/€: **[pixx.io](https://www.pixx.io/)** (DE, dt. Server, DSGVO), [**brandfolder**.com](https://brandfolder.com/), **[OpenText Media Management](https://www.opentext.com/products/media-management)**, uvm.)
- Adobe **Dreamweaver**
	- Desktop: **[BlueGriffon](http://www.bluegriffon.org/)** \[**choco install bluegriffon**\] | **[Google Web Designer](https://webdesigner.withgoogle.com/)** \[**choco install google-web-designer**\]
	- Cloud: **[webflow](https://webflow.com/)**
- Adobe **XD**
	- Desktop: **[JustInMind](https://www.justinmind.com)**
	- Cloud: **[Figma](https://www.figma.com/)**, [mydraft](https://mydraft.cc/), [Moqups](https://moqups.com/), [Framer](https://www.framer.com/), [NinjaMock](https://ninjamock.com/), uvm.
- Adobe **Premiere** / Apple **Final Cut**
	- Desktop: **[OpenShot](https://www.openshot.org/)** \[**choco install openshot**\] | **[Kdenlive](https://kdenlive.org/de/)** \[**choco install kdenlive**\] | **[Shotcut](https://www.shotcut.org/)** \[**choco install shotcut.install**\] | **[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve)** | **[HitFilm Express](https://fxhome.com/product/hitfilm-express)**
- Adobe **Audition**
	- Desktop: **[Audacity](https://www.audacityteam.org/)** \[**choco install audacity**\]
	- Cloud: **[Audiotool](https://www.audiotool.com/)**
- Adobe **After Effects**
	- Desktop: **[Natron](https://natronGitHub.GitHub.io/)** \[**choco install natron.install**\] + **[Blender](https://www.blender.org/)** \[**choco install blender**\]
- Adobe **Captivate** (Screencast)
	- Desktop: **[OBS](https://obsproject.com/)** \[**choco install obs-studio**\] | **[TechSmith Capture](https://www.techsmith.com/learn/tutorials/capture-desktop/capture-app/)** (formerly Jing) \[**choco install capture**\] | **[Screencast-O-Matic](https://screencast-o-matic.com/)** | **[screenrec](https://screenrec.com/)**
	- Spezialhinweis: Man kann auch [mittels **PowerPoint**](https://insider.office.com/de-de/blog/tell-your-story-with-video-recording-in-powerpoint) eine Bild-in-Bild-Aufzeichnung („Teleprompter“) seiner Präsentation machen
- Adobe **Captivate** (E-Learning)
	- Desktop: **[Adapt](https://www.adaptlearning.org/)** | **[Xerte](https://xerte.org.uk/)**
	- Cloud: **[Moodle](https://download.moodle.org/)**
- Apple AirDrop
	- Ad Hoc: **[Local Send](https://localsend.org)** (selbes WLAN benötigt)
	- Continuos: **[Syncthing](https://syncthing.net/)** (bilateral Peer-to-Peer)
- Microsoft **Windows**
	- Desktop: [Linux](https://distrosea.com/)! [BSD](https://de.wikipedia.org/wiki/Berkeley_Software_Distribution)! [ChromeOS](https://chromeos.google/products/chromeos-flex/)!
		- Exotischer: [Solus](https://getsol.us/)! [ReactOS](https://reactos.org/)! BeOS/[Haiku](https://www.haiku-os.org/)!
	- Tipp: Ausprobieren von Linux-Distributionen online per **[DistroSea](https://distrosea.com/)** für Distro-Hoppers
- Microsoft **Office** (Word, Excel, PowerPoint)
	- Spezialhinweis: [Microsoft Office 365](https://www.oth-aw.de/hochschule/services/online-services/microsoft-produkte/) für Studierende kostenlos per Studisoft / OTH-Rahmenvertrag
	- Desktop: **[LibreOffice](https://www.libreoffice.org/)** ⭐ \[**choco install libreoffice-fresh --ignore-dependencies**\] (hoher Funktionsumfang)\
		| [**Collabora Office**](https://www.collaboraonline.com/collabora-office/) for Desktop (technisch basierend auf LibreOffice; mit Ribbons)\
		| **[SoftMaker FreeOffice](https://www.freeoffice.com/)** \[**choco install freeoffice**\] (hohe MS Office UI/UX-Kompatibilität)\
		| [**OnlyOffice** Docs](https://www.onlyoffice.com/desktop.aspx) for Desktop (hohe MS Office Format-Kompatibilität)\
		| [**WPS Office**](https://de.wps.com/download/) (hohe Benutzerfreundlichkeit)\
		| (€:) [**WordPerfect** Office Education](https://www.wordperfect.com/en/product/education-edition/) (hohe/präzise Formatkontrolle)
	- Cloud: **[ZoHo](https://www.zoho.com/)** inkl. [Zoho Docs for Desktop](https://www.zoho.com/docs/help/zoho-docs-for-desktop.html#installing-zohodrive) | [**OnlyOffice** Personal](https://personal.onlyoffice.com/) | **[Google Workspace](https://workspace.google.com/)** ([Google Docs](https://docs.google.com/document/u/0/), [Google Sheets](https://docs.google.com/spreadsheets/u/0/), [Google Slides](https://docs.google.com/presentation/u/0/))
	- Web/Self-Hosted: [APITable](https://github.com/apitable/apitable)
	- Android: **[Collabora Office](https://www.collaboraonline.com/collabora-office-android-ios/)** for Android\
		| SoftMaker **[Office NX](https://play.google.com/store/apps/developer?id=SoftMaker+Software+GmbH)**\
		| [**OnlyOffice**](https://www.onlyoffice.com/office-for-android) for Android\
		| [**WPS Office**](https://de.wps.com/office/android/) for Android
- Microsoft **Word**
	- vgl. Office, hinzu kommen noch weitere nennenswerte Alternativen:
	- Desktop: **[Jarte](https://www.jarte.com/)**
	- Cloud: **[Dropbox Paper](https://paper.dropbox.com/)** | **[YoPad](https://yopad.eu)** | **[EduPad](https://edupad.ch)**
- Microsoft **Excel**
	- vgl. Office, hinzu kommen noch weitere nennenswerte Alternativen:
	- Cloud: **[smartsheet](https://www.smartsheet.com/)**, **[Airtable](https://www.airtable.com/)** (zzgl. obige [ZohoSheets](https://www.zoho.com/sheet/) | [OnlyOffice Personal](https://personal.onlyoffice.com/) | [Google Sheets](https://sheets.google.com/document/u/0/) | [Excel Online](http://office.live.com/start/Excel.aspx))
	- Kollaborative Spreadsheet-Bearbeitung? **[EtherCalc](https://ethercalc.net)**
- Microsoft **PowerPoint**
	- vgl. Office, hinzu kommen noch weitere nennenswerte Alternativen:
	- Desktop: [latex-**beamer**](https://ctan.org/pkg/beamer) bzw. [typst with **touying**](https://typst.app/universe/package/touying/)
	- Web/Self-Hosted: **[reveal.js](https://revealjs.com/)**| [Decker](https://elearning.uni-wuerzburg.de/decker/) | [impress.js](https://github.com/impress/impress.js) | [Shower](https://github.com/shower/shower) | [Inspire.js](https://github.com/LeaVerou/inspire.js) | [deck.js](https://github.com/imakewebthings/deck.js) | [DZSlides](https://github.com/paulrouget/dzslides) | uvm.
	- Cloud: **[slides.com](https://slides.com/)** (basiert auf [reveal.js](https://revealjs.com/))| [genially](https://genially.com/plans/education/) (für Studierende kostenlos) | **[Prezi](https://prezi.com/)** (nur 5 Dokumente kostenlos)\
		| (€:) **[Haiku Deck](https://www.haikudeck.com/pricing/edu)**: KI-gestützte Veredelung von Präsentationen durch automatische Fotos und Designs\
		| (€:) [Microsoft **Sway**](https://sway.cloud.com/)
	- Kollaborative Präsentationen: **[Pitch](https://pitch.com/)**, **[Ludus](https://ludus.one/)**
	- Kollaboratives Zeichnen (Whiteboarding): **[invision](https://www.invisionapp.com/)** | **[miro](https://miro.com/de/)** | **[mural](https://start.mural.co/)**
- Microsoft **Access**
	- Desktop: **[Navicat](https://www.navicat.com/en/products/navicat-premium)**, für Studierende kostenlos über das [Navicat Academic Partner Program for Students](https://www.navicat.com/en/sponsorship/education/student)
	- Web/Self-Hosted: **[nuBuilder](https://www.nubuilder.com/)** | **[budibase](https://budibase.com/pricing/)**
	- Cloud: **[Zoho Creator](https://www.zoho.com/creator/)** | **[Retool](https://retool.com/)** | **[Google AppSheet](https://about.appsheet.com/home/)**
- Microsoft **Outlook** (Groupware)
	- Desktop: **[EssentialPIM Free](https://www.essentialpim.com/features/overview/pro-vs-free)** | [Thunderbird](https://www.mozilla.org/en-US/thunderbird/) \[choco install thunderbird\] | [SeaMonkey](https://www.seamonkey-project.org/) \[choco install seamonkey\]
	- Web/Self-Hosted: [**Zimbra** Open Source Edition](https://www.zimbra.com/open-source-email-overview/) | **[NextCloud Server](https://nextcloud.com/install/)** inkl. [Desktop File Sync Client](https://nextcloud.com/install/#install-clients) | Open Source **[grommunio](https://grommunio.com/download/)**
	- Cloud: **[Zoho Mail](https://www.zoho.com/mail/)** (Forever Free Plan), **[Google Workspace](https://workspace.google.com/)**\
		| [**OnlyOffice** Workspace](https://www.onlyoffice.com/saas.aspx) (u.a. [OnlyOffice Mail](https://www.onlyoffice.com/mail.aspx) und [Calendar](https://www.onlyoffice.com/calendar.aspx))
- Microsoft **OneNote**
	- Desktop: **[Laverna](https://laverna.cc/)**
	- Cloud: **[Notion](https://www.notion.so/)** \[**choco install notion**\] | **[Evernote](https://evernote.com/)** \[**choco install evernote**\] | **[Zoho Notebooks](https://www.zoho.com/notebook/)** | **[Google Keep](https://keep.google.com/)** | uvm.
- Microsoft **Visio**
	- Desktop: **[draw.io](https://app.diagrams.net)** \[**choco install drawio**\]
	- Cloud: [diagrams.net](https://app.diagrams.net)
- Microsoft **Project**
	- Desktop: **[ProjectLibre](https://sourceforge.net/projects/projectlibre/files/ProjectLibre/)** | **[GanttProject](https://www.ganttproject.biz/)**
	- Web/Self-Hosted: **[OpenProject](https://www.openproject.org/)**
	- Cloud: **[Taiga.io](https://www.taiga.io/)**
- **Zoom** bzw. Microsoft **Teams** (Video-Konferenz)
	- Web/Self-Hosted: **[BigBlueButton](https://docs.bigbluebutton.org/greenlight/gl-install.html)** \[via Container\] | **[Jitsi](https://jitsi.org/)** \[**choco install jitsi**\] (für kleine Gruppen) ggf. in Kombination mit einer [rocket.chat](https://www.rocket.chat/)-Integration | **[NextCloud Talk](https://nextcloud.com/talk/)** | **[WorkAdventure](https://github.com/thecodingmachine/workadventure)**
	- Cloud: **[Discord](https://discord.com/)** | **[Jitsi Meet](https://meet.jit.si/)** (für kleine Gruppen) | [**gather**.town](https://www.gather.town/) | [Google **Meet**](https://apps.google.com/meet/) (max. 60 Minuten) | **[HyHyve](https://www.hyhyve.com/pricing/)**
	- (Ergänzungsempfehlung: Für einen hochwertigen virtuellen Hintergrund ohne Greenscreen empfehle ich das kostenpflichtige [XSplit VCam](https://www.xsplit.com/vcam))
	- (Zusatzhinweis: Slack-Alternativen (s. unten) – wie bspw. [Flock](https://www.flock.com/features/communication/video-calling/), [Pumble](https://pumble.com/video-conferencing), [rocket.chat](https://docs.rocket.chat/use-rocket.chat/rocket.chat-conference-call) oder [matrix mittels Element Call](https://call.element.io/) – integrieren ebenfalls Video-Konferenz-Funktionalitäten, haben aber traditionell einen anderen Schwerpunkt.)
- **Slack** bzw. Microsoft **Teams** (kanalbasierte Messaging Tools)
	- Cloud: **[Flock](https://www.flock.com/pricing)** oder **[Pumble](https://pumble.com/pricing)** bzw. auch [Mattermost Cloud](https://mattermost.com/pricing/#cloud) (oder [Discord](https://discord.com/), welches aber enge File-Upload-Restriktionen für kostenlose User, also ohne Nitro-Abo, hat)
	- Self-Hosted/Open-Source: **[Mattermost](https://mattermost.com/pricing/)**, **[rocket.chat](https://www.rocket.chat/)** oder **[Matrix](https://matrix.org/)** (Matrix per **[Synapse](https://matrix.org/docs/projects/server/synapse)** als Homeserver und mit diversen Client-Optionen, u.a. [**Element** Web/Desktop](https://matrix.org/docs/projects/client/element) sowie Element [Android](https://play.google.com/store/apps/details?id=im.vector.app)/[iOS](https://itunes.apple.com/gb/app/vector.im/id1083446067?mt=8); übrigens hieß Element früher Riot)
- **[Virbela](https://www.virbela.com/)**, **[ivCAMPUS](https://www.ivicos.eu/)** bzw. **[CampFire](https://www.campfire.to/)** (Metaverse)
	- Self-Hosted: **[WorkAdventure](https://github.com/thecodingmachine/workadventure)**
	- Cloud: [**gather**.town](https://www.gather.town/) | **[HyHyve](https://www.hyhyve.com/pricing/)**
- Microsoft **SharePoint** (ECM/CMS)
	- Web/Self-Hosted: [**Alfresco** Community Edition](https://www.hyland.com/en/resources/alfresco-community-download) (Java; [github](https://github.com/Alfresco/alfresco-community-repo))
	- (Groupware-Aspekte: vgl. MS Outlook Alternativen)
	- (Projektmanagement-Aspekte: vgl. MS Project Alternativen)
	- (Wiki-Aspekte: vgl. Atlassian Confluence Alternativen auf der [SWE-Schwesterseite](https://github.com/cyberlytics/awesome-software-engineering-tools#kostenlose-alternativen))
- Document Management Systeme (DMS) {reduzierter als ECM/CMS}
	- (Ebenfalls [**Alfresco** Community Edition](https://www.hyland.com/en/resources/alfresco-community-download), siehe bei ECM/CMS)
	- Web/Self-Hosted: [DocSpell](https://docspell.org/#feature-selection) (Java), [Paperless](https://github.com/paperless-ngx/paperless-ngx) (Python)
- Microsoft Windows Search (Desktop Search Engine / Lokale Volltextsuche)
	- [DocFetcher](https://docfetcher.sourceforge.io/de/index.html) (Java) \[choco install docfetcher\], auch als Portable App
		- Basierend auf Apache Lucene (Volltextindexierung) und Apache Tika (Extraktion von Textinhalten und Metadaten aus verschiedenen Dokumentformaten)
	- [Anytxt Searcher](https://anytxt.net/)
	- Nennenswert: CLI-Suche in mehreren PDFs (ohne Indexierung)
		- CLI: **[ripgrep-all](https://github.com/phiresky/ripgrep-all)** \[**choco install ripgrep-all**\], **[SeekFast](https://seekfast.org/download-seekfast)**
- **cPanel** / **Plesk** / … (Small Business Linux Server)
	- **[KeyHelp](https://www.keyhelp.de)** (Linux-only), Deutsche Herkunft (kostenlos aber closed source)
		- Primär: Websites/Domains, Mail-Accounts, FTP und Fileserver
		- (FOSS-Alternativen zu KeyHelp im engeren Sinn: Froxlor, ISPConfig, i-MSCP)
	- **[WikiSuite](https://wikisuite.org)** (Linux-only), Internationales FOSS-Herkunft
		- Großes Bündel an Unternehmensfunktionalitäten: Mail-Accounts, Websites/Domains, FTP, Fileserver, Groupware, Chat, VidConf, CRM, Payment, …
		- Weit jenseits von Einzelaspekten wie KeyHelp (klassischer SMB Linux Server) oder auch NextCloud (Groupware)
- **SAS** Enterprise Miner / IBM **SPSS** (Data Mining / Statistical Spreadsheets)
	- Desktop:
		- **[KNIME](https://www.knime.com/)** \[**choco install knime**\]
		- **[RapidMiner](https://rapidminer.com/platform/)** for Academics mit [Educational License Program](https://rapidminer.com/platform/educational/) \[**choco install rapidminer**\]
			- (im Kern ist [RapidMiner Studio auch Open Source](https://github.com/rapidminer/rapidminer-studio))
		- **[PSPP](https://www.gnu.org/software/pspp/)** \[**choco install pspp**\]: free replacement for SPSS
		- **[JASP](https://jasp-stats.org/)** \[**choco install jasp**\]
		- **[Jamovi Desktop](https://www.jamovi.org/features.html)** \[**choco install jamovi**\]
		- (ggf. Interactive Notebooks: bspw. [Juyter](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html) via Docker \[**docker run -p 8888:8888 jupyter/scipy-notebook**\])
	- Cloud:
		- **[Jamovi Cloud](https://cloud.jamovi.org/)**
		- **[Posit Cloud](https://posit.cloud/)**
		- **[CoCalc](https://cocalc.com/)**: Collaborative Computation and Data Science
		- (ggf. Interactive Notebooks: bspw. [Google **Collab**](https://colab.research.google.com/))
	- Weiterführende Referenzen:
		- siehe auch Abschnitt **[Data Science](https://github.com/cyberlytics/awesome-bdccai-tools#data-science)** auf der Schwester-Seite zu BDCC/AI
		- Diskussion: [chatbot](https://www.perplexity.ai/search/new?q=Which+open-source+alternatives+exist+for+SAS%3F)
		- SAS/GRAPH: Python (matplotlib, seaborn, Plotly), R (ggplot2, lattice)
		- SAS/STAT or SAS/ETS: R + Python + Gretl + SciPy/statsmodels
- Wolfram **Mathematica** / MapleSoft **Maple** (Symbolic Math / Computer Algebra System = CAS)
	- Desktop: **[Mathics](https://mathics.org/)**
	- Web/Self-Hosted: **[SageMath](https://www.sagemath.org/)** (Integration von NumPy, SciPy, matplotlib, Sympy, Maxima, GAP, FLINT, R, uvm.)
	- Kommandozeile: [FriCAS](https://fricas.github.io/) (Interpreter, Compiler und riesige Bibliothek sowie auch Jupyter-Integration)
	- Cloud: **[CoCalc](https://cocalc.com/)**, **[Wolfram Cloud](https://www.wolframcloud.com/)** (introductory plan)
	- (Zur Einordnung: [CAS-Funktionalität](https://en.wikipedia.org/wiki/List_of_computer_algebra_systems))
- MathWorks **MATLAB** (Numerical Computation)
	- vgl. Mathematica/Maple/Magma, hinzu kommen noch weitere nennenswerte Alternativen:
	- Desktop: **[Scilab](https://www.scilab.org/)**, GNU **[Octave](https://octave.org/)**
	- Cloud: **[Octave Online](https://octave-online.net/)**
		- (für die Cloud ggf. ebenfalls Scilab per Cloud-basierter Zugang via Plattformen wie **[CoCalc](https://cocalc.com/)**)
	- (Der Vollständigkeit halber: MATLAB beinhaltet neben numerical computing auch [CAS-Funktionalität](https://en.wikipedia.org/wiki/List_of_computer_algebra_systems) wie Mathematica/Maple, das ist aber nicht MATLABs Sweet-Spot)
- Autodesk **Maya** / Autodesk **3DS Max** / Maxon **Cinema 4D** / SideFx **Houdini** / Maxon **ZBrush** (3D Digital Content Creation; All-In-One)
	- Desktop: **[Blender](https://www.blender.org/)** \[**choco install blender**\]
	- Nur als Studierende:
		- **[Maya](https://www.autodesk.de/education/edu-software/overview)** \[**choco install maya**\] (One-Year Educational Access)
		- **[3DS Max](https://www.autodesk.de/education/edu-software/overview)** \[**choco install 3dsmax**\] (One-Year Educational Access)
		- **[Cinema 4D](https://www.maxon.net/en/educational-licenses)** (Educational, Six-month, renewable)
		- **[Houdini](https://www.sidefx.com/education/education-programs/students/#free_software)** (Free Apprentice Edition)
	- Cloud: [Spline](https://spline.design/)
- Autodesk **MotionBuilder** / Reallusion **iClone** (3D Animationen; ohne umfangreich zu modellieren oder riggen)
	- Destkop: Valve [Source FilmMaker](https://store.steampowered.com/app/1840/Source_Filmmaker/) (SFM)
- Bondware **Poser** / Reallusion **Character Creator** (3D Character Modeler)
	- Destkop: [Daz 3D](https://www.daz3d.com)
	- FOSS: [MakeHuman](http://www.makehumancommunity.org/) (sowie dessen Variante [MPFB2](https://static.makehumancommunity.org/mpfb/downloads.html) als Add-On für Blender)
- Blackmagic Design: **DaVinci Resolve Studio** (Post-Production)
	- Kostenlose Variante: **[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve)**
- Foundry **[Nuke VFX](https://www.foundry.com/products/nuke-family/nuke)** (Post-Producton: Node-based Compositing/VFX)
	- Nennenswerte AI-Erweiterung: **[Copy Cat](https://learn.foundry.com/nuke/content/reference_guide/air_nodes/copycat.html)**
	- €€€-Konkurrent: Blackmagic Design **[Fusion](https://www.blackmagicdesign.com/products/fusion)**
	- FOSS/Desktop: **[Blender VFX](https://www.blender.org/features/vfx/)**
- Steinberg **Cubase** / Emagic|Apple **Logic** /	Ableton **Live** / Presonus **Studio One** / Image-Line **FL Studio** / Digital Audio Workstation (DAW)
	- FOSS: **[Ardour](https://ardour.org/)**
		- Weitere kostenlose Varianten: Cockos **[Reaper](https://www.reaper.fm/)** (60d kostenlos, dann Nag-Screen), [Garageband](https://www.apple.com/mac/garageband/) (nur macOS)
	- Nennenswerte Plugins:
		- (€) Antares [Auto-Tune](https://www.antarestech.com/products/auto-tune/), z.B. kostengünstige Einsteigerversion [Access](https://www.antarestech.com/products/auto-tune/access) ([Video](https://www.youtube.com/watch?v=3kfsVaeSvHw))

## Android Apps

- Mail Client
	- Einstiegsfreundlich: [Thunderbird Mobile](https://www.thunderbird.net/mobile/) ([direct download](https://github.com/thunderbird/thunderbird-android/releases) / [Play Store](https://play.google.com/store/apps/details?id=net.thunderbird.android)) (auf Basis von [K-9 Mail](https://k9mail.app/) mit weiterhin eigenständigem Release per selbigem [direct download](https://github.com/thunderbird/thunderbird-android/releases) und via [Play Store](https://play.google.com/store/apps/details?id=com.fsck.k9))
	- Power-User: [FairEmail](https://email.faircode.eu/) ([direct download](https://github.com/M66B/FairEmail/releases) / [Play Store](https://play.google.com/store/apps/details?id=eu.faircode.email)) (Marcel aka M66B ist auch der Autor von NetGuard)
- Privacy: Anti-Ads/-Trackers
	- [AdGuard](https://adguard.com/adguard-android/overview.html) (Direct download, only! Non-Play-Store.)
- Firewall:
	- [NetGuard](https://netguard.me/) ([direct download](https://github.com/M66B/NetGuard/releases) / [Play Store](https://play.google.com/store/apps/details?id=eu.faircode.netguard)) (Marcel aka M66B ist auch der Autor von FairEmail)
- Authenticator
	- Twilio [Authy](https://www.authy.com/) ([Play Store](https://play.google.com/store/apps/details?id=com.authy.authy))
- Dateiaustausch / AirDrop-Alternative
	- [LocalSend](https://github.com/localsend/localsend) ([direct download](https://github.com/localsend/localsend/releases) / [Play Store](https://play.google.com/store/apps/details?id=org.localsend.localsend_app))
- PDF Viewer
	- [MJ PDF](https://github.com/mudlej/mj_pdf) (Direct download, only! Non-Play-Store.)
- Instant Messaging / Chat Systeme / WhatsApp- bzw. iMessage-Alternative
	- [Signal](https://github.com/signalapp/Signal-Android) ([direct download](https://github.com/signalapp/Signal-Android/releases) / [Play Store](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms)) «Centralized» \[Telegram, Threema, etc. pp.\]
	- [Matrix](https://matrix.org/ecosystem/clients/) via [FluffyChat](https://github.com/krille-chan/fluffychat) ([direct download](https://github.com/krille-chan/fluffychat/releases) / [Play Store](https://play.google.com/store/apps/details?id=chat.fluffy.fluffychat)) «Decentralized» \[Jabber/XMPP, Chat/IRC, E-Mail, etc. pp.\]
	- [Wir haben keine Herausforderung mit den Angeboten. Sondern mit der Unification!](https://xkcd.com/1810/)

## Bonus: 3D-Printing

- Begegnungen / Creative Retreat
	- FabLab (u.a. in [Nürnberg](https://fablab-nuernberg.de/) und [Erlangen](https://fablab.fau.de/))
	- [OTH-AW MakerLab](https://www.oth-aw.de/hochschule/kooperationen/makerspace/) in Amberg
- Einstieg:
	- instructables [3D Printing Basics](https://www.instructables.com/3D-Printing-Basics/)
	- Drucker-Bestenliste: [cnet](https://www.cnet.com/tech/computing/best-3d-printer/) uvm.
- Repos für 3D-Print-Modelle:
	- Universell: [Thingiverse](https://www.thingiverse.com/)
	- Bambu-Lab-Printer-zentrisch: [MakerWorld](https://makerworld.com/3d-models)
	- Prusa-Printer-zentrisch: [printables](https://printables.com)
	- Search Engine for 3D: [yeggi](https://www.yeggi.com/)
- Kuratierte 3D-Print-Modelle:
	- phrozen [Cool 3D Prints](https://phrozen3d.com/blogs/guides/cool-3d-prints)
	- Cults3D [Useful, functional and practical 3D prints](https://cults3d.com/en/collections/best-useful-functional-practical-3d-prints)
	- Eigene Empfehlungen:
		- [Pringles-Schiebeschale](https://makerworld.com/models/1461894-pringles-chips-slider-tray-with-a-functional-lid)
	- Für Kinder:
		- [Flexi Rex](https://github.com/DrLex0/print3D-FlexiRex)
		- [Flussotter](https://makerworld.com/models/1457412-cute-river-otter-articulated)
		- [Flexi Cat](https://makerworld.com/models/1452423-flexi-cat-new-design)
		- [Schlüsselanhänger mit Namen](https://makerworld.com/models/1467612-parametric-name-keychain)
		- [Stempel](https://makerworld.com/models/1037541-stamp-maker-customizable-stamps)
		- [Baby Dragon](https://www.printables.com/model/349385-baby-dragon)
		- [Dragon](https://www.printables.com/model/1196735-dragon-on-pedestal-figure)
- On-Demand Online-Fertigung
	- DE: [Xometry](https://get.xometry.eu/), [Zelta3D](https://zelta3d.de/), [3DDesign24](https://www.3ddesign24.de/), etc.
- Weiterführende Referenzen: [Awesome 3D Printig](https://github.com/ad-si/awesome-3d-printing)

## Appendix: More Free Student Stuff

- [GitHub Student Developer Pack](https://education.github.com/pack)
- [discount-for-student-dev](https://github.com/AchoArnold/discount-for-student-dev)
- [A-to-Z-Resources-for-Students](https://github.com/dipakkr/A-to-Z-Resources-for-Students)

## Footer

### Future Work

I plan to translate this awesome list from German into English at some point.

### Contribute

What did I miss? Anything you recommend?

Contributions are most welcome, please adhere to the contribution guidelines and ensure your pull request adheres to the following guidelines:

- Make an individual pull request for each suggestion.
- Keep descriptions short and simple.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- Try to make your Pull request and title as descriptive as possible.
- New categories or improvements to the existing categorization are welcome.

Thank you for your suggestions!

### Backers

Thank you to all our supporters! 🙏

_Please, consider supporting my work as a lot of effort takes place to generate this list! Thanks a lot._

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-0070BA?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=QTDJ2JA58ZM9L)

[![Support on Ko‑fi](https://img.shields.io/badge/Support-Ko–fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/cyberlytics)

[![Buy Me A Coffee!](https://img.shields.io/badge/buy_me_a_coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/cyberpetaneuron)

### License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under Creative Commons [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/) .
