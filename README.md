# Portfólio - João Carlos Ruiz Casali II

Portfólio profissional de página única para **João Carlos Ruiz Casali II**, com posicionamento como **Analista Ambiental**.

O site apresenta experiência em regularização ambiental, CAR/SICAR, recuperação de áreas degradadas, TCRA, AIA, PGRS, PMGIRS, geoprocessamento, QGIS, AutoCAD, levantamentos de campo e documentação técnica.

## Demo

Após publicar no GitHub Pages, o site ficará disponível em um endereço semelhante a:

```text
https://seu-usuario.github.io/nome-do-repositorio/
```

Se o repositório usar domínio personalizado, substitua o link acima pelo endereço final.

## Objetivo

O projeto transforma os materiais profissionais fornecidos em um portfólio estático, responsivo e compatível com GitHub Pages.

A narrativa prioriza:

- Indicadores agregados de atuação.
- Casos anonimizados.
- Clareza técnica.
- Credibilidade profissional.
- Privacidade de clientes, propriedades e processos.

Nenhum mapa real, coordenada, documento técnico de cliente, número de processo, propriedade, aprovação ou resultado não comprovado foi publicado.

## Tecnologias

- HTML5 semântico.
- CSS3 com variáveis.
- JavaScript puro.
- Layout mobile-first.
- Hospedagem estática via GitHub Pages.

## Estrutura

```text
index.html
styles.css
script.js
README.md
assets/
├── images/
│   └── territorio-abstrato.svg
├── icons/
│   └── favicon.svg
└── curriculo-joao-carlos.pdf
```

## Como Executar Localmente

Abra o arquivo `index.html` diretamente no navegador.

Também é possível servir por HTTP:

```powershell
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Como Publicar No GitHub Pages

1. Envie os arquivos para um repositório no GitHub.
2. No GitHub, acesse `Settings`.
3. Entre em `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Escolha a branch principal, geralmente `main`.
6. Selecione a pasta `/root`.
7. Salve a configuração.

O GitHub Pages publicará o site usando o `index.html` da raiz do repositório.

## Direção Visual

A identidade visual usa uma paleta ambiental técnica:

- Verde floresta como cor principal.
- Verde escuro para títulos e contraste.
- Verde oliva para apoio visual.
- Azul-petróleo para ações e destaque tecnológico.
- Creme e branco para fundos claros.

O visual abstrato foi inspirado em curvas de nível, parcelas territoriais, rios e camadas de geoprocessamento. Ele é autoral e genérico, sem uso de coordenadas ou dados reais de clientes.

## Responsividade

O layout foi validado para mobile, tablet e desktop.

- Em telas abaixo de `720px`, o hero usa altura natural para evitar vazios excessivos.
- O visual abstrato do hero fica oculto no mobile e aparece em telas maiores.
- Os botões principais ocupam a largura total no mobile.
- As seções mobile não dependem de animação para aparecer.
- O menu mobile possui altura máxima e rolagem interna.
- O site respeita `prefers-reduced-motion`.

## Acessibilidade E Interações

- Navegação fixa.
- Menu mobile acessível.
- Foco visível.
- Links externos seguros com `rel="noopener noreferrer"`.
- Rolagem suave.
- Destaque da seção ativa.
- Animações leves com `IntersectionObserver` em telas maiores.

## Validações

- Cargo mantido como **Analista Ambiental**, sem senioridade inventada.
- Datas, contatos, LinkedIn e indicadores conferidos com os materiais fornecidos.
- Casos mantidos anonimizados.
- Experiências não alinhadas ao posicionamento ambiental não foram incluídas.
- Sintaxe do JavaScript validada com:

```powershell
node --check script.js
```

## Materiais Que Podem Ser Adicionados Futuramente

- Foto profissional real e autorizada.
- Currículo final diagramado em PDF.
- Certificados com carga horária e credenciais.
- Mapas autorais feitos com dados públicos.
- Estudos técnicos anonimizados.
- Relatórios, plantas ou imagens somente com autorização formal e dados sensíveis removidos.

## Licença E Uso

Este portfólio foi criado para uso profissional de João Carlos Ruiz Casali II. O conteúdo pessoal, currículo, contatos e textos profissionais não devem ser reutilizados para terceiros sem autorização.
