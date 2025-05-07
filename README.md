[//]: # (Title: Awesome Abschlussarbeit Informatik/KI)
[//]: # (Language: de-DE)
[//]: # (Licence: CC BY 4.0)
[//]: # (Kurztitel: Werkzeuge » Abschlussarbeiten)
[//]: # (Lemma: tools-thesis)

# Awesome Abschlussarbeit (Informatik/KI)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Made With Love](https://img.shields.io/badge/Made%20With-Love-orange.svg)](https://github.com/chetanraj/awesome-github-badges)

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
- [Generative KI](#generative-ki)
- [LaTeX & PDF](#latex--pdf)
- [Schreiben](#schreiben)
- [Anti-Prokrastination](#anti-prokrastination)
- [Translations](#translations)
- [Evaluation-Werkzeuge](#evaluation-werkzeuge)
- [Management & Agile Methoden](#management--agile-methoden)
- [Kollaborative Werkzeuge](#kollaborative-werkzeuge)
- [Zeichnen](#zeichnen)
- [Presentations](#presentations)
- [Plug-Ins / Add-Ins / Extensions](#plug-ins--add-ins--extensions)
- [Bildmaterialien](#bildmaterialien)
- [Mathe](#mathe)
- [Job-Bewerbungen](#job-bewerbungen)
- [Kostenlose Alternativen](#kostenlose-alternativen)
- [Appendix: More Free Student Stuff](#appendix-more-free-student-stuff)
- [Footer](#footer)
  - [Future Work](#future-work)
  - [Contribute](#contribute)
  - [Backers](#backers)
  - [License](#license)

<!-- tocstop -->

## Literaturrecherche & Wissensaufbau

- [Google **Scholar**](https://scholar.google.com) | **[ResearchGate](https://www.researchgate.net/)** | **[Semantic Scholar](https://www.semanticscholar.org)**
	- DE: [**DBLP** Computer Science Bibliography](https://dblp.org/) | [**BASE**: Bielefeld Academic Search Engine](https://www.base-search.net/)
- Fortgeschrittene Websuchen: Google [Advanced Search](https://www.google.com/advanced_search) (Liste of [Search Operators](https://ahrefs.com/blog/google-advanced-search-operators/)) | Google [Advanced Image Search](https://www.google.com/advanced_image_search)
	- Clean Google Search result URLs: [URL clean](https://urlclean.com/)
- KI-gestützte Literaturrecherche: [ResearchRabbit](https://www.researchrabbit.ai/), [Open Knowledge Maps](https://openknowledgemaps.org/), [Connected Papers](https://www.connectedpapers.com), [Consensus](https://consensus.app/search/), uvm.
	- Weitere Referenzen: [Georgetown Univ.-Bib. Liste](https://guides.library.georgetown.edu/ai/tools)
- Drei Informatik-Primärquellen: **[SpringerLink](https://link.springer.com/)**, **[ACM](https://dl.acm.org/)**, **[IEEE](https://ieeexplore.ieee.org/Xplore/home.jsp)**
- **[Publish or Perish](https://harzing.com/resources/publish-or-perish)**: Desktop Applikation mit intergrierten Autoren-Metriken
- Suche in mehreren PDFs? **[ripgrep-all](https://github.com/phiresky/ripgrep-all)** \[**choco install ripgrep-all**\] | **[SeekFast](https://seekfast.org/download-seekfast)**
- Fancy Cloud-/AI-Stuff (€): **[scite\_](https://scite.ai/)** und **[Iris.ai](https://the.iris.ai/)**
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
- Persönliches Wissensmanagement / Zettelkasten / Notizen
	- **[Obsidian](https://obsidian.md/)** \[**choco install obsidian**\]: Zettelkasten und Notizen ([Obsidian **Video**-Tutorial: **Zettelkasten** für Beginner](https://www.youtube.com/watch?v=svqJ8BUh8mU))
	- **[Notion](https://www.notion.so/)** \[**choco install notion**\]: Notizen und Kollaboration
	- (Gegenüberstellung von [Obsidian vs. Notion](https://mattgiaro.com/zettelkasten-obsidian-notion/), aus der Perspektive Zettelkasten)
	- Vgl. ggf. zusätzlich die OneNote-Alternativen im Abschnitt [Kostenlose Alternativen](#kostenlose-alternativen)
- Weiterführende Quellen: [Tools for Academic Research](https://tools.kausalflow.com/tools/) ([lineare Variante](https://github.com/emptymalei/awesome-research))

## Generative KI

Die Verwendung von generativer KI zur Text-Erstellung Ihrer Abschlussarbeit ist Ihnen durch meine eigenen Policies untersagt. Dennoch können Sie sich die diversen Werkzeuge zu Nutzen machen, bspw. als persönlicher KI Tutor.

- Extensions
	- Browser
		- Grammatik: [LanguageTool](https://languagetool.org/de/chrome)
		- LLM u.a. für GMail: [Halist AI](https://chromewebstore.google.com/detail/halist-ai/fbpfkdadaghhgfcnaljbkjmfaaclohdb)
		- Weitere Referenzen: [Tooltivity-Liste](https://tooltivity.com/categories/ai)
	- Thunderbird
		- [ThunderAI](https://addons.thunderbird.net/en-US/thunderbird/addon/thunderai/)
- Desktop-Apps / AI Tool Installer:
	- Universell: **[pinokio](https://pinokio.computer/)**, [SEAIT](https://github.com/diStyApps/seait/)
- Text-to-Text:
	- LLM Model-Benchmark: [What LLM Provider](https://whatllm.vercel.app/) | [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) ([Method](https://huggingface.co/docs/leaderboards/open_llm_leaderboard/about)) sowie [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)
		- LLM Modelle mit DE-Unterstützung: [Webartikel](https://medium.com/@oledawidzinski/deutschsprachige-open-source-llms-als-alternative-zu-chatgpt-und-co-8ecbcf6ab96d) (u.a. Mistral-Nemo-Instruct-2407, DiscoLM_German_7b_v1, SauerkrautLM, …, Qwen2-7B-Instruct, Llama3-DiscoLeo-Instruct-8B, …)
		- Long-Term Context LLM / Personalized AI: [MemGPT](https://memgpt.ai/)
		- Agent AI: **[Letta](https://github.com/letta-ai/letta)**
	- Local/Desktop/Offline: **[Msty](https://msty.app/)** ⭐, **[LM Studio](https://lmstudio.ai/)** ⭐, Nomic [gpt4all](https://github.com/nomic-ai/gpt4all), [Jan AI](https://jan.ai) und andere
		- Local [OpenAI-compatible API](https://platform.openai.com/docs/api-reference/chat) Server: [LM Studio OpenAI-compatible API server](https://lmstudio.ai/docs/api/openai-api), [vLLM OpenAI-compatible API Server](https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html), [Msty Local AI Service](https://docs.msty.app/how-to-guides/make-local-ai-service-available-on-the-network), [gpt4all API Server](https://docs.gpt4all.io/gpt4all_api_server/home.html), [Jan.ai Cortex Local API Server](https://cortex.so/docs/quickstart/) ([API](https://cortex.so/api-reference/))
		- Let LLMs run code locally: [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter)
	- Local/Embedded/Offline: [vLLM](https://github.com/vllm-project/vllm)
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
		- AI-Coder Model-Benchmark: [Eval Plus](https://evalplus.github.io/leaderboard.html)
		- Local/Desktop/Offline: **[Msty](https://msty.app/)** ⭐, **[LM Studio](https://lmstudio.ai/)** ⭐
		- Cloud/freemium: [DeepSeek Chat](https://chat.deepseek.com/) ,Online [Eden AI](https://www.edenai.co/), [uvm.](https://codesubmit.io/blog/ai-code-tools/)
		- Nennenswerte andere Dev-Tools: [dir-assistant](https://github.com/curvedinf/dir-assistant)
		- Weiterführende Referenzen: [Awesome AI-Powered Developer Tools](https://github.com/jamesmurdza/awesome-ai-devtools) | [Awesome Code-AI](https://github.com/sourcegraph/awesome-code-ai)
	- Text-to-SQL:
		- Foundational Models: [DuckDB NSQL](https://github.com/NumbersStationAI/DuckDB-NSQL)
		- Tutorials: AWS Machine Learning [Build a robust text-to-SQL solution ](https://aws.amazon.com/de/blogs/machine-learning/build-a-robust-text-to-sql-solution-generating-complex-queries-self-correcting-and-querying-diverse-data-sources/), LlamaIndex [Text-to-SQL Guide with Jupyter](https://docs.llamaindex.ai/en/stable/examples/index_structs/struct_indices/SQLIndexDemo/), IBM Watson [Generating SQL from text with LLMs](https://developer.ibm.com/tutorials/awb-text-to-sql-using-llms/), 
	- Text-to-Image:
		- AI-Image-Generator Model-Benchmark: Artificial Analysis [Image AI Model & Provider Leaderboard](https://artificialanalysis.ai/text-to-image) | [Benchmarking-Awesome-Diffusion-Models](https://github.com/Schuture/Benchmarking-Awesome-Diffusion-Models)
		- Dev/FOSS Models: **[Stable Diffusion](https://github.com/CompVis/stable-diffusion)**, **[FLUX.1](https://github.com/black-forest-labs/flux)**
		- Local/Desktop/Offline: Lykos **[Stability Matrix](https://lykos.ai/downloads)** ⭐ (Tutorial: [Using FLUX.1 locally](https://www.kdnuggets.com/using-flux-1-locally)), Stable Diffusion WebUI [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge) bzw. [reForge](https://github.com/Panchovix/stable-diffusion-webui-reForge), [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
		- Cloud/freemium-with-API: [Playground](https://playground.com/design/pricing), [PicoGen](https://picogen.io/), [Pollinations AI](https://pollinations.ai/)
		- Cloud/freemium: [Deep Dream Generator](https://deepdreamgenerator.com/) ([old version](https://deepdreamgenerator.com/generator?old-tools=1)), [Dezgo](https://dezgo.com/text2image/sdxl), [Stable Diffusion Online](https://stablediffusionweb.com/) (10img/d; mit Wasserzeichen), [NightCafe](https://creator.nightcafe.studio/), [WPimages](https://www.wpimagines.com/), [AI Image Generator](https://www.aiimagegenerator.org/), [uvm.](https://easywithai.com/best-free-ai-image-generators/)
		- Cloud/€€€/Subscriptions: **[OpenArt](https://openart.ai/create)** ⭐, OpenAI [**DALL·E** 2](https://labs.openai.com/waitlist), **[Midjourney](https://www.midjourney.com/)**, [craiyon](https://www.craiyon.com/) (früher: „DALL·E mini“), Google [Imagen](https://imagen.research.google/), Adobe [Firefly](https://www.adobe.com/products/firefly.html) …
	- Text-to-Video: [synthesia](https://www.synthesia.io), [kaiber.ai](https://kaiber.ai), … , China: [Kling](https://kling.kuaishou.com/en)
	- Text-to-Slides: **[gamma](https://gamma.app/)** ⭐, [SlidesPilot](https://www.slidespilot.com/), [SlideSpeak](https://slidespeak.co/), [ChatBA](https://www.chatba.com/), …
	- Text-to-Quiz: [Quizalize](https://app.quizalize.com/pricing), …
	- Text-to-Speach (TTS): [NaturalReader](https://www.naturalreaders.com/online/), [TTSMaker](https://ttsmaker.com/), [Murf.AI](https://murf.ai/text-to-speech), …
	- Text-to-Sound: [boomy](https://boomy.com/), [Suno AI](https://app.suno.ai/), [Vocaloid](https://www.vocaloid.com/en/vocaloid6/), Google [Instrument Playground](https://artsandculture.google.com/experiment/instrument-playground/8QFo2oQr2uT3pg?hl=en), …
	- Text-to-3D / Image-to-3D: [csm.ai](https://www.csm.ai) (zzgl. €: [3D AI Studio](https://www.3daistudio.com))
	- AI-Suites/API-centric/Pay-as-you-Go: **[Fireworks AI](https://fireworks.ai/)**, [Replicate](https://replicate.com/)
	- Weiterführende Referenzen: [There is an AI for that](https://theresanaiforthat.com/most-saved/) | [There's an AI](https://theresanai.com/)
- IT-Security:
	- [WormGPT](https://thehackernews.com/2023/07/wormgpt-new-ai-tool-allows.html)
- Weiterführende Quellen
	- Werkzeugsammlungen: **[FutureTools](https://www.futuretools.io)** | [Awesome AI Tools](https://tools.awesomechatgpt.com) #1 | [Awesome AI Tools](https://github.com/mahseema/awesome-ai-tools) #2 | Altern [Awesome AI Tools](https://github.com/mahseema/awesome-ai-tools) #3 | [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) #1 | [Awesome Generative AI](https://github.com/filipecalegario/awesome-generative-ai) #2 | [Awesome AGI](https://github.com/EmbraceAGI/Awesome-AGI) | [Awesome GPT](https://github.com/formulahendry/awesome-gpt) | [Awesome GPT-4](https://gpt4.tools) | [Awesome Bots](https://github.com/DopplerHQ/awesome-bots)
	- Prompting: [Awesome **ChatGPT Prompts**](https://github.com/f/awesome-chatgpt-prompts)

## LaTeX & PDF

- DISCLAIMER: **[typst](https://typst.app/) vs. LaTeX**? Mit typst gibt es eine moderne, überlegene Typesetting-Variante zu latex, die aber technisch völlig eigenständig ist.
	- Überlegen Sie ggf. Publikationen oder Abschlussarbeiten in typst zu schreiben; nur fehlt dann ggf. die einfache Vorlage (aber mind. [IEEE](https://typst.app/universe/package/charged-ieee/) gibt es sowie erste Drafts zu [ACM](https://typst.app/universe/package/clean-acmart))
	- Mit [touying](https://touying-typ.github.io/) gibt es eine gute Altternative zu latex-beamer in typst
	- Weiterführende Quellen: [Awesome Typst](https://github.com/qjcg/awesome-typst)
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
- **[TeXstudio](https://www.texstudio.org/)** \[**choco install texstudio.install**\] ⭐: Ein Fork von Texmaker, früher auch TexMakerX genannt
	- Sowohl MikTeX als auch Sumatra PDF vor den Editoren installieren, da diese sich tlw. beim ersten Start gleich für beides konfigurieren
	- Alternativen: [TeXnicCenter 2.0](https://www.texniccenter.org) \[**choco install texniccenter**\], [Kile](https://kile.sourceforge.io/) \[**choco install kile**\], [Texmaker](https://www.xm1math.net/texmaker/) \[**choco install texmaker**\] sowie der in MikTeX und TeX Live enthaltene [TeXworks](https://tug.org/texworks) | speziell unter Mac/iOS: [Texifier](https://www.texifier.com/) oder [TeXShop](https://pages.uoregon.edu/koch/texshop/) | Gesamtübersicht: [LaTeX Editors/IDEs](https://tex.stackexchange.com/questions/339/latex-editors-ides)
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
- Sonstige Werkzeuge
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

## Schreiben

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
	- Cloud: [experte.de **Barrierefreiheit Test**](https://www.experte.de/barrierefreiheit), [web accessibility evaluation tool (**WAVE**)](https://wave.webaim.org/), [Accessible Colors](https://accessible-colors.com/), [TPG ARC Scan](https://www.tpgi.com/free-website-accessibility-scan/) (formerly: Cynthia Says) sowie ebenfalls [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/)
	- Browser Add-In: **[Axe](https://www.deque.com/axe/)**, **[WAVE](https://wave.webaim.org/extension)**, [Siteimprove](https://addons.mozilla.org/firefox/addon/si-accessibility-checker/)
- User tracking and analysis: **[Amplitude](https://amplitude.com/)**

## Management & Agile Methoden

- Kalenderwoche: [aktuelle-**kalenderwoche**.org](https://www.aktuelle-kalenderwoche.org/)
- Zeitzonen: **[worldtimebuddy](https://www.worldtimebuddy.com/)**, [Time Zone Map](https://www.timeanddate.com/time/map/)
- Ganttcharts:
	- Desktop: FOSS [Agantty](https://www.agantty.com/)
	- Web: [Agantty](https://www.agantty.com/), [team gantt](https://www.teamgantt.com/), [toggl plan](https://toggl.com/plan/)
- Kanban-Board: **[Wekan](https://wekan.GitHub.io/)** «Self-hosted»
- Timer: **[Boxing Interval Timer](https://boxingtimer.org/)** oder [Online-Stopwatch](https://www.online-stopwatch.com/timer/5minutes/) (5min) etc. pp.
- Time Tracking? **[TopTracker](https://www.toptal.com/tracker)**
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
	- Es gibt eine [Visio Stencils Datei für E/R-Modellierung und erweiterte E/R-Modellierung](https://www.cyberlytics.eu/theses/templates/ERD-Chen76_EERD-ElmasriNavathe94.vss) aus meiner eigenen Feder
	- Derzeit ist Visio mutmaßlich nicht in der Microsoft Office 365 Pro Variante enthalten, die Sie kostenlos über studisoft.de beziehen können; aber Visio ist Teil der [Microsoft Azure Dev Tools for Teaching](https://www.oth-aw.de/hochschule/services/online-services/downloads-software/), welche für Studierende ebenfalls kostenlos zur Verfügung stehen
- Adobe **Illustrator**: Für ambitionierte Vektorgrafiken.
	- Illustrator erlaubt das Öffnen von PDFs und eignet sich dadurch gut zur Extraktion von Grafiken, ggf. in hochauflösendem Vektorformat.
	- Über die Zugehörigkeit zur OTH-AW müssten Sie auch einen Zugang zur Adobe Creative Cloud bekommen können
- [**draw.io**/diagrams.net](https://app.diagrams.net): Universelles Zeichenwerkzeug, u.a. auf Augenhöhe mit Microsoft Visio.
	- Unterstützt ebenfalls Notationen wie UML und E/R-Diagramme
	- Entweder als Cloud-WebApp oder als Desktop-Anwendung
	- (Unter Windows bspw. mittels chocolatey: **choco install drawio**)
- **[Krita](https://krita.org/)**: Open Source Alternative für Photoshop, also für Rastergrafiken
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
- **[DirectPoll](https://directpoll.com)**: Abstimmungssystem („Clicker“), also Umfragen und Votings bei Großgruppen
	- Alternativen bei Großgruppen:
		- Cloud: **[OnlineTED](https://onlineted.de/)** Basic (max. 100 Teilnehmer) | **[Tweedback](https://tweedback.de/)** Free (nur 24h Session-Dauer) | **[Mentimeter](https://www.mentimeter.com)** (max. 2 Fragen pro Präsentation) | [**vevox**.com](https://www.vevox.com/pricing/education-pricing) (Multiple-Choice-Fragen kostenlos; früher meetoo.io)
		- Self-Hosted: **[Arsnova](https://gitlab.com/particify/dev/foss/arsnova)** bzw. Particify \[via [Docker](https://gitlab.com/particify/dev/foss/docker-orchestration)\]
		- Desktop: **[FreeQuizDome](https://www.freequizdome.com/)**
	- Alternativen für kleinere Gruppen: **[PollEveryWhere](https://www.polleverywhere.com/)** Intro (max. 25 Teilnehmer, aber PPT-Integration) \[**choco install polleverywhere**\] | **[Kahoot!](https://kahoot.com/register/kahoot-study-pricing/)** (max. 10 Teilnehmer) | **[AhaSlides](https://ahaslides.com/pricing/)** (max. 7 Teilnehmer; mit [PowerPoint-Extension](https://ahaslides.com/blog/extension-for-powerpoint/))
	- Beispielfragen: [90 Mentimenter-Beispiele](https://www.mentimeter.com/de-DE/blog/awesome-presentations/85-poll-questions-for-every-occasion)
- Videos für eine Präsentation beschleunigen oder verlangsamen: [Online Video Cutter » Change Video Speed](https://online-video-cutter.com/change-video-speed)

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
	- **Concepts**/Nouns: **[Noun Project](https://thenounproject.com/)** [⭐⭐](https://www.htmlsymbols.xyz/unicode/U+2B50) (Absolutely awesome! Free of charge with attributions, but account required.)
	- **Fotos/Bilder:** **[Unsplash](https://unsplash.com/de)**, **[pixabay](https://pixabay.com/)** ⭐
		- Weitere: [Pexels](https://www.pexels.com/)
	- **Illustrationen:** **[unDraw](https://undraw.co/)** ⭐
		- Weitere: [clker](http://www.clker.com), [pixabay](https://pixabay.com/vectors/) (mit Filter auf „Vectors“)
	- **Icons:** **[iconmonstr](https://iconmonstr.com)**, [**Feather** (OSS)](https://feathericons.com), [**FontAwesome** (Freebies)](https://fontawesome.com/v6/search?o=r&m=free), **[Emojis](https://www.webfx.com/tools/emoji-cheat-sheet/)**, **[CryptoKit](https://cryptokit.ch/specimen)**
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

- **[MathCha.io](https://www.mathcha.io)**: Eine Cloud-WebApp zum zeichnen von mathematischen Grafiken.
	- Erlaubt den Export nach SVG und sogar nach Tikz (Latex) Format.
- **[Geogebra](https://moodle.oth-aw.de/mod/url/view.php?id=86125)**: Graphikrechner, 2D Geometrie, 3D Geometrie, Algebra-Rechner, …
	- (Auch als Desktop-App unter Windows verfügbar, bspw. mittels chocolatey: **choco install geogebra6** bzw. **choco install geogebra-geometry**)
	- Alternative: **Desmos** ([Desmos Calculator](https://moodle.oth-aw.de/mod/url/view.php?id=86074), [Desmos Geometry](https://moodle.oth-aw.de/mod/url/view.php?id=86075))

## Job-Bewerbungen

\[ Parallel zur Abschlussarbeit werden Sie mit der Jobsuche und Ihren Bewerbungen beginnen. \]

- Weitere Tipps: vgl. [Schwesterseite](https://github.com/cyberlytics/awesome-basics#bsc-bonusliste)
- Lebenslauf-Werkzeuge für Informatiker:
	- LaTeX: **[CV-Templates](https://de.overleaf.com/latex/templates/tagged/cv)** (mein eigenes Paket: [ECV](https://ctan.org/pkg/ecv))
	- Web: [Free **Responsive HTML5 Website Template**](https://www.google.de/search?q=Free+Responsive+HTML5+Website+Template)
	- Entwickler-CV: **[JSON resume](https://jsonresume.org/)**
	- Cloud Resume Builder: bspw. [CakeResum](https://www.cakeresume.com/), [zety](https://zety.com/), [Resume Genius](https://resumegenius.com/), uvm.

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
- Adobe **LightRoom**
	- Desktop: **[DarkTable](https://www.darktable.org/)** \[**choco install darktable**\] | **[RawTherapee](https://www.rawtherapee.com/)** \[**choco install rawtherapee**\]
	- Cloud: **[polarr](https://photoeditor.polarr.co/)**
- Adobe **Dreamweaver**
	- Desktop: **[BlueGriffon](http://www.bluegriffon.org/)** \[**choco install bluegriffon**\] | **[Google Web Designer](https://webdesigner.withgoogle.com/)** \[**choco install google-web-designer**\]
	- Cloud: **[webflow](https://webflow.com/)**
- Adobe **XD**
	- Desktop: **[JustInMind](https://www.justinmind.com)**
	- Cloud: **[Figma](https://www.figma.com/)**, [mydraft](https://mydraft.cc/), [Moqups](https://moqups.com/), [Framer](https://www.framer.com/), [NinjaMock](https://ninjamock.com/), uvm.
- Adobe **Premiere**
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
- Adobe **Experience Manager** bzw. **MediaValet** (Media Asset Management bzw. Digital Asset Management = DAM)
	- Web/Self-Hosted: **[AtroDAM](https://www.atrodam.com/)** (und [weitere](https://www.softwaresuggest.com/digital-asset-management-software/open-source))
	- Cloud: (€:) **[pixx.io](https://www.pixx.io/)** (DE, dt. Server, DSGVO), (€:) [**brandfolder**.com](https://brandfolder.com/), (€:) **[OpenText Media Management](https://www.opentext.com/products/media-management)**, uvm.
- Apple AirDrop
	- Ad Hoc: **[Local Send](https://localsend.org)** (selbes WLAN benötigt)
	- Continuos: **[Syncthing](https://syncthing.net/)** (bilateral Peer-to-Peer)
- Microsoft **Office** (Word, Excel, PowerPoint)
	- Spezialhinweis: [Microsoft Office 365](https://www.oth-aw.de/hochschule/services/online-services/microsoft-produkte/) für Studierende kostenlos per Studisoft / OTH-Rahmenvertrag
	- Desktop: **[LibreOffice](https://www.libreoffice.org/)** \[**choco install libreoffice-fresh --ignore-dependencies**\]\
		| **[SoftMaker FreeOffice](https://www.freeoffice.com/)** \[**choco install freeoffice**\]\
		| [**OnlyOffice** Docs](https://www.onlyoffice.com/desktop.aspx) for Desktop\
		| (€:) [**WordPerfect** Office Education](https://www.wordperfect.com/en/product/education-edition/)
	- Cloud: **[ZoHo](https://www.zoho.com/)** inkl. [Zoho Docs for Desktop](https://www.zoho.com/docs/help/zoho-docs-for-desktop.html#installing-zohodrive) | [**OnlyOffice** Personal](https://personal.onlyoffice.com/) | **[Google Workspace](https://workspace.google.com/)** ([Google Docs](https://docs.google.com/document/u/0/), [Google Sheets](https://docs.google.com/spreadsheets/u/0/), [Google Slides](https://docs.google.com/presentation/u/0/))
	- Web/Self-Hosted: [APITable](https://github.com/apitable/apitable)
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
	- Desktop: [latex-**beamer**](https://ctan.org/pkg/beamer)
	- Web/Self-Hosted: **[reveal.js](https://revealjs.com/)**| [Decker](https://elearning.uni-wuerzburg.de/decker/) | [impress.js](https://github.com/impress/impress.js) | [Shower](https://github.com/shower/shower) | [Inspire.js](https://github.com/LeaVerou/inspire.js) | [deck.js](https://github.com/imakewebthings/deck.js) | [DZSlides](https://github.com/paulrouget/dzslides) | uvm.
	- Cloud: **[slides.com](https://slides.com/)** | [genially](https://app.genial.ly/) (für Studierende kostenlos) | **[Prezi](https://prezi.com/)** (nur 5 Dokumente kostenlos)\
		| (€:) **[Haiku Deck](https://www.haikudeck.com/)**: KI-gestützte Veredelung von Präsentationen durch automatische Fotos und Designs\
		| (€:) [Microsoft **Sway**](https://sway.office.com/)
	- Kollaborative Präsentationen: **[Pitch](https://pitch.com/)**
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
- Microsoft **SharePoint** (Enterprise DMS/CMS)
	- Web/Self-Hosted: [**Alfresco** Community Edition](https://www.alfresco.com/products/community/download)
	- (Groupware-Aspekte: vgl. MS Outlook Alternativen)
	- (Projektmanagement-Aspekte: vgl. MS Project Alternativen)
	- (Wiki-Aspekte: vgl. Atlassian Confluence Alternativen auf der [Schwesterseite](https://github.com/cyberlytics/awesome-software-engineering-tools#kostenlose-alternativen))
- **cPanel** / **Plesk** / … (Small Business Linux Server)
	- **[KeyHelp](https://www.keyhelp.de)** (Linux-only), Deutsche Herkunft (kostenlos aber closed source)
		- Primär: Websites/Domains, Mail-Accounts, FTP und Fileserver
		- (FOSS-Alternativen zu KeyHelp im engeren Sinn: Froxlor, ISPConfig, i-MSCP)
	- **[WikiSuite](https://wikisuite.org)** (Linux-only), Internationales FOSS-Herkunft
		- Großes Bündel an Unternehmensfunktionalitäten: Mail-Accounts, Websites/Domains, FTP, Fileserver, Groupware, Chat, VidConf, CRM, Payment, …
		- Weit jenseits von Einzelaspekten wie KeyHelp (klassischer SMB Linux Server) oder auch NextCloud (Groupware)
- MathWorks **Matlab** / Wolfram **Mathematica**
	- Desktop: **[SageMath](https://www.sagemath.org/)**, **[Octave](https://octave.org/)**
	- Cloud: **[CoCalc](https://cocalc.com/)**, **[Wolfram Cloud](https://www.wolframcloud.com/)** (introductory plan)
- Autodesk **Maya** / Autodesk **3DS Max** / Maxon **Cinema 4D** / SideFx **Houdini**
	- Desktop: **[Blender](https://www.blender.org/)** \[**choco install blender**\]
	- Nur als Studierender:
		- **[Maya](https://www.autodesk.de/education/edu-software/overview)** \[**choco install maya**\] (One-Year Educational Access)
		- **[3DS Max](https://www.autodesk.de/education/edu-software/overview)** \[**choco install 3dsmax**\] (One-Year Educational Access)
		- **[Cinema 4D](https://www.maxon.net/en/educational-licenses)** (Educational, Six-month, renewable)
		- **[Houdini](https://www.sidefx.com/education/education-programs/students/#free_software)** (Free Apprentice Edition)
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

[![Buy Me A Coffee please!](https://cdn.buymeacoffee.com/buttons/default-orange.png)](https://www.buymeacoffee.com/cyberpetaneuron)

### License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under Creative Commons [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/) .
