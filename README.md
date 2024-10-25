# Vamos criar o conteúdo do README.md como um arquivo markdown.

readme_content = """
# Mapeamento Interativo do IFCE

Este projeto é um mapeamento interativo do Instituto Federal do Ceará (IFCE), permitindo que os alunos explorem visualmente o campus e obtenham informações sobre áreas específicas ao clicar nos blocos do mapa.

## Objetivo do Projeto

O objetivo é oferecer uma experiência interativa onde:
- Um **clique único** exibe informações sobre a área escolhida.
- Um **duplo clique** redireciona para um link externo com mais recursos ou informações sobre o bloco.

## Estrutura do Projeto

O projeto é composto por:
- **Arquivo HTML**: Define a estrutura do mapa e as áreas clicáveis.
- **Imagem SVG do Mapa** (`estruturaIfce.svg`): Representa o layout visual do campus IFCE.
- **JavaScript**: Gerencia as interações de clique e exibição de informações.

### Mapa de Áreas Clicáveis

Cada área representa um bloco do campus e possui uma configuração de clique, com coordenadas delimitando os espaços. Abaixo estão os blocos com suas descrições e redirecionamentos:

| Bloco      | Descrição                     | Redirecionamento                                                                                           |
|------------|--------------------------------|-----------------------------------------------------------------------------------------------------------|
| Bloco 1    | Informações sobre o Bloco 1    | [YouTube Inkscape Tutorials](https://www.youtube.com/results?search_query=inkscape+tutorials)              |
| Bloco 2    | Informações sobre o Bloco 2    | [Inkscape Wiki](https://wiki.inkscape.org/wiki/index.php/Main_Page)                                       |
| Bloco 3    | Informações sobre o Bloco 3    | [Vecteezy](https://www.vecteezy.com)                                                                       |
| Bloco 4    | Informações sobre o Bloco 4    | [Design Tutorials](https://design.tutsplus.com/categories/vector)                                         |
| Bloco 5    | Informações sobre o Bloco 5    | [Inkscape](https://inkscape.org)                                                                           |
| Bloco 6    | Informações sobre o Bloco 6    | [Inkscape Forum](https://inkscape.org/forums/)                                                             |
| Bloco 7    | Informações sobre o Bloco 7    | [Freepik](https://www.freepik.com)                                                                         |
| Bloco 8    | Informações sobre o Bloco 8    | [Envato Elements](https://elements.envato.com/)                                                            |
| Bloco 9    | Informações sobre o Bloco 9    | [Adobe Color](https://color.adobe.com/create)                                                              |

## Como Executar o Projeto

1. Clone este repositório ou baixe os arquivos.
2. Abra o arquivo `index.html` em um navegador para visualizar o mapa interativo.
3. Passe o mouse sobre as áreas do mapa e clique para experimentar as funcionalidades de clique único e duplo clique.

## Funcionalidades Futuras

- Links internos para páginas dedicadas a cada bloco.
- Informações detalhadas de horários e eventos dos blocos.
- Inclusão de pontos de interesse como bibliotecas, laboratórios, e áreas de convivência.

## Contribuição

Se deseja contribuir com o projeto, siga os passos abaixo:
1. Faça um fork deste repositório.
2. Realize as alterações desejadas.
3. Submeta um Pull Request para revisão.
"""

# Salvando o conteúdo em um arquivo README.md
with open("/mnt/data/README.md", "w") as file:
    file.write(readme_content)

"/mnt/data/README.md"
