Title: BTools
Authors: b3m2a1
Categories: Development
Creator: b3m2a1@gmail.com
Description: A general purpose package that implements useful functionality for application development. 			Features include: distribution tools, documentation generation, front-end manipulation, and application editing 			  
DisplayName: BTools
Extensions: <|Kernel -> <|Root -> ., Context -> {BTools`}|>, Resource -> <|Root -> Resources, Resources -> {Icons, Images, PaletteGenerators, Templates, Themes, {PacletIcon, Icons/PacletIcon.png}, {PacletSiteIcon, Icons/PacletSiteIcon.png}, {GoogleOAuthExample, Images/GoogleOAuthExample.png}, {AppManagerPaletteGenerator, PaletteGenerators/AppManagerPaletteGenerator.nb}, {CuratedDataHelperGenerator, PaletteGenerators/CuratedDataHelperGenerator.nb}, {DocumentationGenerator, PaletteGenerators/DocumentationGenerator.nb}, {EncodedCacheManagerGenerator, PaletteGenerators/EncodedCacheManagerGenerator.nb}, {HTMLHelperGenerator, PaletteGenerators/HTMLHelperGenerator.nb}, {PacletServerManagerGenerator, PaletteGenerators/PacletServerManagerGenerator.nb}, {PaletteTemplate, PaletteGenerators/PaletteTemplate.nb}, {PelicanHelperGenerator, PaletteGenerators/PelicanHelperGenerator.nb}, {ServiceConnectionHelperGenerator, PaletteGenerators/ServiceConnectionHelperGenerator.nb}, {SiteBuilderGenerator, PaletteGenerators/SiteBuilderGenerator.nb}, {ContextLoader, Templates/ContextLoader.wl}, {CuratedDataTemplate, Templates/CuratedDataTemplate.nb}, {init, Templates/Initialization/init.m}, {Main, Templates/Initialization/Main.wl}, {README, Templates/README.nb}, {ServiceConnectionTemplate, Templates/ServiceConnectionTemplate.nb}, {Frameworks, Templates/Frameworks}, {CuratedData, Templates/Frameworks/CuratedData}, {$ServiceConnection, Templates/Frameworks/$ServiceConnection}, {Initialization, Templates/Initialization}, {Loader, Templates/Initialization/Loader}, {SiteBuilder, Templates/SiteBuilder}, {DocumentationSite, Templates/SiteBuilder/DocumentationSite}, {PacletServer, Templates/SiteBuilder/PacletServer}, {TutorialSite, Templates/SiteBuilder/TutorialSite}, {WebSite, Templates/SiteBuilder/WebSite}, {minimal, Themes/minimal}, {static, Themes/minimal/static}, {templates, Themes/minimal/templates}, {template_lib, Themes/template_lib}, {include, Themes/template_lib/include}, {tipuesearch, Themes/template_lib/tipuesearch}}|>, FrontEnd -> <|Prepend -> True|>, PacletServer -> <|Tags -> {documentation, front-end, paclets, web}, Categories -> {Development}, Description -> A general purpose package that implements useful functionality for application development.                       , License -> MIT|>, Documentation -> <|Language -> English, MainPage -> Guides/BTools|>|>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       			Features include: distribution tools, documentation generation, front-end manipulation, and application editing                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       			  
License: MIT
Modified: Missing[NotAvailable]
Name: BTools
Slug: btools
Tags: documentation,front-end,paclets,web
Thumbnail: PacletIcon.png
URL: https://github.com/b3m2a1/mathematica-BTools
Version: 2.1.37

<a id="btools" class="Section" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

# BTools

![BTools]({filename}/img/BTools/PacletIcon.png)

A general purpose package that implements useful functionality for application development.
   Features include: distribution tools, documentation generation, front-end manipulation, and application editing
     

---

<a id="install" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Install

**Before installing, be sure to check out the ** **[Change Log](https://paclets.github.io/PacletServer/pages/log.html)** ** to make sure that you trust the developer.**

To install this paclet, run:

    << https://paclets.github.io/PacletServer/Install.wl
    PublicPacletInstall["BTools"]

Depending on what the current value of  ```$ContextPath``` is you may also need to first run

    Needs["PacletManager`"]

*  To update it, replace  ```PacletInstall``` with  ```PacletUpdate``` . 

*  To uninstall replace  ```PacletInstall``` with  ```PacletUninstall``` and remove the  ```"Site"``` parameter.

---

<a id="basic-information" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Basic Information

<a id="name" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### Name

BTools

<a id="version" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### Version

2.1.37

<a id="creator" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### Creator

[b3m2a1@gmail.com](mailto:b3m2a1@gmail.com)

<a id="url" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### URL

[https://github.com/b3m2a1/mathematica-BTools](https://github.com/b3m2a1/mathematica-BTools)

<a id="license" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### License

MIT

---

<a id="extra-information" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Extra Information

This package provides no extra information

---

<a id="extensions" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Extensions

<a id="kernel" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### Kernel

*  Root: .

*  Context: BTools`

<a id="resource" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### Resource

*  Root: Resources

*  Resources

  *  Icons

  *  Images

  *  PaletteGenerators

  *  Templates

  *  Themes

  *  {PacletIcon, Icons/PacletIcon.png}

  *  {PacletSiteIcon, Icons/PacletSiteIcon.png}

  *  {GoogleOAuthExample, Images/GoogleOAuthExample.png}

  *  {AppManagerPaletteGenerator, PaletteGenerators/AppManagerPaletteGenerator.nb}

  *  {CuratedDataHelperGenerator, PaletteGenerators/CuratedDataHelperGenerator.nb}

  *  {DocumentationGenerator, PaletteGenerators/DocumentationGenerator.nb}

  *  {EncodedCacheManagerGenerator, PaletteGenerators/EncodedCacheManagerGenerator.nb}

  *  {HTMLHelperGenerator, PaletteGenerators/HTMLHelperGenerator.nb}

  *  {PacletServerManagerGenerator, PaletteGenerators/PacletServerManagerGenerator.nb}

  *  {PaletteTemplate, PaletteGenerators/PaletteTemplate.nb}

  *  {PelicanHelperGenerator, PaletteGenerators/PelicanHelperGenerator.nb}

  *  {ServiceConnectionHelperGenerator, PaletteGenerators/ServiceConnectionHelperGenerator.nb}

  *  {SiteBuilderGenerator, PaletteGenerators/SiteBuilderGenerator.nb}

  *  {ContextLoader, Templates/ContextLoader.wl}

  *  {CuratedDataTemplate, Templates/CuratedDataTemplate.nb}

  *  {init, Templates/Initialization/init.m}

  *  {Main, Templates/Initialization/Main.wl}

  *  {README, Templates/README.nb}

  *  {ServiceConnectionTemplate, Templates/ServiceConnectionTemplate.nb}

  *  {Frameworks, Templates/Frameworks}

  *  {CuratedData, Templates/Frameworks/CuratedData}

  *  {$ServiceConnection, Templates/Frameworks/$ServiceConnection}

  *  {Initialization, Templates/Initialization}

  *  {Loader, Templates/Initialization/Loader}

  *  {SiteBuilder, Templates/SiteBuilder}

  *  {DocumentationSite, Templates/SiteBuilder/DocumentationSite}

  *  {PacletServer, Templates/SiteBuilder/PacletServer}

  *  {TutorialSite, Templates/SiteBuilder/TutorialSite}

  *  {WebSite, Templates/SiteBuilder/WebSite}

  *  {minimal, Themes/minimal}

  *  {static, Themes/minimal/static}

  *  {templates, Themes/minimal/templates}

  *  {template_lib, Themes/template_lib}

  *  {include, Themes/template_lib/include}

  *  {tipuesearch, Themes/template_lib/tipuesearch}

<a id="frontend" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### FrontEnd

*  Prepend: True

<a id="documentation" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

### Documentation

*  Language: English

*  MainPage: Guides/BTools