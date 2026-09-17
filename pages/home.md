---
standalone: true
title: Home
slug: home
projeto: ''
pageSettings:
  language: pt-BR
  link_pt_br: '#'
  link_en: '#'
  link_es: '#'
  animations: enable_all
  direction: left
  seoTitle: ''
  seoDescription: ''
  seoKeywords: []
  seoImage: ''
pageTheme:
  primaryColor: '#f5f5f5'
  secondaryColor: '#3c8bc8'
  highlightColor: '#f2e3e3'
  auxiliaryColor: '#ffb514'
  displayFont: ''
  textFont: ''
  spacingPatterns:
    - name: 10px
      mobile: 10px
      tablet: 10px
      desktop: 10px
pageInclude: null
modules:
  - type: MapBox
    style: mapbox://styles/mfabricio-pmrp/cmtvlzm0n00fp01qodfzifrsl
    token: pk.eyJ1IjoibWZhYnJpY2lvLXBtcnAiLCJhIjoiY210dDFmZzc2MDJ3azJ6b201dTNhZGxobiJ9.TDxddkHOjhSthrFOQArX4Q
    centerLng: '-21.168'
    centerLat: '-47.831'
    zoom: '11.78'
    bearing: '0'
    pitch: '0'
    layers: ''
    columnAlign: center
    floatingText: false
    views:
      - id: map1_view1
        centerLng: '-21.151'
        centerLat: '-47.840'
        zoom: '16.12'
        mobileZoom: '16.12'
        duration: '2000'
        bearing: '0'
        pitch: '0'
        layers: ''
        title: ''
        notes: ''
        items: []
components:
  - type: Group
    id: main
    shortTitle: Bem-Vindo
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                # Bem-vindos à Documental

                #### Sua plataforma de software livre para a criação de geo-narrativas.
        column2:
          components:
            - type: Spacer
              desktop: 130px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: |-
                Para começar a trabalhar em seu projeto, selecione o modo Editor ou Tela dividida na parte superior esquerda, em seguida, clique em "Work with local repository" para escolher a pasta do projeto em seu computador.

                Para saber mais sobre as possibilidades e opções de aplicação dos blocos temáticos, clique no link abaixo. (ou não)
            - type: Spacer
              desktop: 30px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: https://documental.xyz/docs
                target: _blank
                text: Guia de Instalação & Uso
              icon: ''
              size: ''
  - type: Map
    id: Mapa 1
    shortTitle: Teste
    longTitle: Teste
    description: ''
    showInMenu: true
    animations: true
    txtColor: ''
    bgColor: ''
    components:
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_view1
    columnAlign: center
    floatingText: false
---
