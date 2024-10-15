# AVTOKYO2024 Talks

## Mozilla Firefox 0-day:ブラウザサイドチャネルによるインストールアプリケーション特定攻撃
**講演概要：** Mozilla Firefoxの0-day脆弱性である、URLプロトコルハンドラを利用したブラウザサイドチャネル攻撃を扱います。
本攻撃では、ブラウザがURLプロトコルハンドラを処理する際の微細な挙動差をオラクル(情報源)として利用し、ターゲットユーザの環境にインストールされているアプリケーションの特定を可能とします。
本脆弱性に対しては新たに複数のCVE番号が払い出されており、URLプロトコルハンドラが漏洩した場合のプライバシー/セキュリティリスクから、発見の経緯と攻撃のメカニズムについても深掘りします。
本発表は、Webブラウザ環境における攻撃手法に関心を持つセキュリティ研究者や開発者を対象としています。

※本脆弱性は2024年11月16日時点で修正されています。

**講演者紹介：** Webアプリケーションつんつん職人。CTFプレイヤー、バグハンターとして活動。SECCON CTFの運営メンバ、AVTOKYO2020および2023の登壇、DEF CON CTF Finalsへ出場。GoogleやFirefoxを含む多数のWebサイトやソフトウェアの脆弱性を発見し報告している。

**[PDF (日本語)](AVTOKYO2024_ja.pdf)**  

## Mozilla Firefox 0-day: Browser Side-Channel Attack to Leak Installed Applications
**Abstract :** This presentation focuses on a 0-day vulnerability in Mozilla Firefox, which is a browser side-channel attack leveraging the URL protocol handler. 
The attack exploits subtle behavioral differences in how the browser handles URL protocol requests, using them as an oracle to identify applications installed in the target's machine. 
Several CVE numbers have been assigned to this vulnerability, and we will delve into how I discovered and attacked the bug, addressing the privacy and security risks posed by the URL protocol handler leaks. 
This talk is aimed at security researchers and developers interested in attacks against modern web browsers.

Note: This vulnerability was patched as of November 16, 2024.

**Speakers Bio :** Cybersecurity Enthusiast, CTF Player and Bug Hunter. Contributed to the organization of SECCON CTF, took the stage at AVTOKYO2020/2023, and competed in the DEF CON CTF Finals. Renowned for uncovering and reporting vulnerabilities in web services and softwares including Google and Firefox.

**[PDF (English)](AVTOKYO2024_en.pdf)**  