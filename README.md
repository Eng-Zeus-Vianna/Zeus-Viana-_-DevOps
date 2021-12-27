# Zeus-Viana-_-DevOps
Atualização Zeus

habilitarRobotsTXT: verdadeiro
buildDrafts: falso
buildFuture: falso
buildExpired: falso

minificar:
    desativarXML: verdadeiro
    minifyOutput: verdadeiro

idiomas:
  en:
    idiomaNo nome: Inglês
    peso: 10
    homeInfoParams:
      Título:  "Hello" 
      Conteúdo: Meu nome é Zeus. Sou Analista de Sistemas, brasileiro que mora em Lisboa POrtugal.
    menu:
      principal:
        - identificador: categorias
          nome: categorias
          url: /categorias/
          peso: 10
        - identificador: tags
          nome: tags
          url: /tags/
          peso: 20
        - identificador: sobre
          nome: sobre
          url: /about/
          peso: 20
        - identificador: faq
          nome: faq
          url: /faq/
          peso: 20

  pt:
    idiomaSNo nome: Português Português
    peso: 20
    homeInfoParams:
      Título:  "Olá \U0001F44B" 
      Conteúdo: Meu nome é Zeus. Sou Analista de Sistemas, brasileiro que mora em Lisboa POrtugal.
    menu:
      principal:
        - identificador: categorias
          nome: categorias
          url: /categorias/
          peso: 10
        - identificador: tags
          nome: tags
          url: /tags/
          peso: 20
        - identificador: sobre
          nome: sobre
          url: /about/
          peso: 20
        - identificador: perguntas
          nome: perguntas
          url: /faq/
          peso: 20

params:
    env: produção   # para ativar o google analytics, opengraph, twitter-cards e esquema.
    título: Stephany Nusch
    descrição:  "Blog de tecnologia" 
    palavras-chave: [Blog, Portfólio, ]
    autor: Me
    # autor: ["Eu", "Você"] # vários autores
    imagens: ["<link ou caminho de imagem para opengraph, twitter-cards>"]
    DateFormat:  "2 de janeiro de 2006" 
    padrãoEleme: escuro   # escuro, luz
    desativarThemeToggle: falso

    ShowReadingTime: verdadeiro
    ShowShareButtons: verdadeiro
    ShowPostNavLinks: verdadeiro
    ShowBreadCrumbs: verdadeiro
    ShowCodeCopyButtons: falso
    desativarSpecial1stPost: falso
    desativarScrollToTop: falso
    comentários: falso
    hidemeta: falso
    hideSummary: falso
    showtoc: falso
    tocopen: falso

    ativos:
        # desativarHLJS: verdadeiro # para desativar destaque.js
        # desativaçãoFingerprinting: verdadeiro
        favicon:  "<link / abs url>" 
        favicon16x16:  "<link / abs url>" 
        favicon32x32:  "<link / abs url>" 
        apple_touch_icon:  "<link / abs url>" 
        safari_pinned_tab:  "<link / abs url>" 

    rótulo:
        texto:  "Stephany" 
        #ícone: /ícone de toque de maçã.png
        iconHeight: 35

    # modo perfil
    perfilMode:
        habilitado: falso   # precisa ser explicitamente definido
        título: Zeus Vianna
        legenda:  "Tech Blog" 
        imageUrl:  "<img localização>" 
        imageWidth: 120
        imageHeight: 120
        imagemTitle: minha imagem
        botões:
            - nome: Posts
              url: posts
            - nome: Tags
              url: tags

    # modo home-info
   

    socialIcons:
 
        - nome: github
          url:  "https://github.com/Eng-Zeus-Vianna" 
        - nome: linkedin
          url:  "https://www.linkedin.com/in/zeus--3b5480143/" 
        - nome: e-mail
          url: zeus.devops@outlook.com

    #análises:
    #    google:
    #        SiteVerificationTag: "XYZabc"
    #    bing:
    #        SiteVerificationTag: "XYZabc"
    #    yandex:
    #        SiteVerificationTag: "XYZabc"

    cobertura:
        oculta: true   # hide everywhere but not in structured datas
        hiddenInList: true   # hide on list pages and home
        hiddenInSingle: true   # hide on single page


    # para pesquisa
    https://fusejs.io/api/options.html
    fuseOpts:
        isCaseSensitive: falso
        shouldSort: verdade
        localização: 0
        distância: 1000
        limiar: 0.4
        minMatchCharLength: 0
        teclas: ["título", "permalink", "resumo", "conteúdo"]
