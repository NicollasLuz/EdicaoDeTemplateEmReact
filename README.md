# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


##

# Alterações feitas no código da aula "Atividade: Edição de Template em React – Simulação de Trabalho Real"

O código teve alterações no main.css nas linhas:
    124: 
    onde era:   --color-orange-1: #E8543E;
    e foi para:   --color-orange-1: #ff812d;

    9494: 
    onde era:   color: var(--color-green-1) !important;
    e foi para:   color: #ff8800 !important;

Também teve alterações no plano de fundo principal do site onde tirei a imagem padrão do site e coloquei a imagem de um plano de fundo do mario. As imagem que ficavam no fundo eu tambem alterei, onde era as imagens de fundo cinza com a dimensão da imagem, e alterei-as para imagens de personagens do filme do Mario. A imagem de um professor que ficava pa parte inicial, foi alterada para a imagem da princesa peach.

O App.jsx também foi otimizado, onde tinha partes do codigo que não era utilizado como o:
            <Route path="home-2" element={<HomePage2 />} />
              <Route path="home-3" element={<HomePage3 />} />
              <Route path="home-4" element={<HomePage4 />} />
              <Route path="home-5" element={<HomePage5 />} />
              <Route path="home-6" element={<HomePage6 />} />
              <Route path="home-7" element={<HomePage7 />} />
              <Route path="home-8" element={<HomePage8 />} />
              <Route path="home-9" element={<HomePage9 />} />
              <Route path="home-10" element={<HomePage10 />} /> 


onde essa parte do código nao era utilizado, pois foi pedido que removesse as paginas de home.

No CourseDetailsSix.jsx alterei a cor do botão de verde para laranja:
244: 
    <button className="button -md -outline-green-1 text-green-1 w-1/1">
    <button className="button -md -outline-orange-7 text-orange-7 w-1/1">

No Buttons.jsx também alterei a cor:
34: 
    <button className="button -md -outline-green-1 text-green-1">
    <button className="button -md -outline-orange-1 text-orange-1">

E também traduzi os textos da página inicial, tirando de inglês e passando para português 

E por fim apaguei algumas pastas de coisas que não estava usando, como os homes a fim de otimizar o site 