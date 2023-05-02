<template>
  <!--Area header-->
  <header>
    <div class="header-width">
      <img src="../../public/images/logo.jpg" alt="" />

      <div class="search">
        <input
          type="text"
          class="searchTerm"
          placeholder="Procure por produtos marcas ou nomes"
        />
        <a href="" class="searchButton">
          <img
            src="../../public/images/imgIcons/buscar.jpg"
            alt=""
            class="busca"
          />
        </a>
      </div>
      <div class="orange t1">
        <h3 class="orange">Olá, bem vindo(a)!</h3>

        <div class="center">
          <a href="">Entre </a>
          <span class="orange"> <span style="color: #000"> ou </span> </span>

          <a href="">Cadastre-se </a>
        </div>
      </div>
 <!--Carrinho-->
      <a href="#"><h2 class="orange t">Meu carrinho</h2></a>
    </div>

    <nav class="index1">
      <div class="nav">
        <div class="header-width">
          <div class="menu">
            <div class="select-menu">
              <div class="select-btn">
                 
                <ol>
                  <li><a href="#">Ver toda Loja ></a>
                    <ul> <!--MENU-->
                      <li><a href="#">Ar Condicionado ></a></li>
                      <li><a href="#">Ventilação ></a></li>
                      <li><a href="#">Eletrodomésticos ></a></li>
                      <li><a href="#">Eletroportábeis ></a></li>
                      <li><a href="#">Casa Inteligente ></a></li>
                      <li><a href="#">Comércio e Indústria ></a></li>
                      <li><a href="#">Máquinas e Ferramentas ></a></li>
                      <li><a href="#">Materiais de instalação ></a></li>
                      <li><a href="#">Fluído Gás Refrigerante ></a></li>
                      <li><a href="#">Peças ></a></li>
                    </ul>
                  </li>
                  </ol>
                
              </div>
 
            </div>
          </div>
 <!--Sub menu-->
          <div class="menu1">
            <ul class="ul-menu">
              <div class="icon"></div>
              <div></div>

              <li>
                <div class="img-center">
                  <img
                    src="../../public/images/imgIcons/icon-ar.jpg"
                    alt=""
                    class="display"
                  />
                </div>
                <a href="#">Ar condicionado</a>
              </li>
              <div class="division"></div>

              <li>
                <div class="img-center">
                  <img
                    src="../../public/images/imgIcons/icon-eletro.jpg"
                    alt=""
                    class="display"
                  />
                </div>
                <a href="#">Eletrodomésticos</a>
              </li>

              <div class="division"></div>

              <li>
                <div class="img-center">
                  <img
                    src="../../public/images/imgIcons/icon-eletro2.jpg"
                    alt=""
                    class="display"
                  />
                </div>
                <a href="#">Eletroportáteis</a>
              </li>
              <div class="division"></div>

              <li>
                <div class="img-center">
                  <img
                    src="../../public/images/imgIcons/industria.jpg"
                    alt=""
                    class="display"
                  />
                </div>
                <a href="#">Comércio e Indústria</a>
              </li>
              <div class="division"></div>

              <li>
                <div class="img-center">
                  <img
                    src="../../public/images/imgIcons/icon-pecas.jpg"
                    alt=""
                    class="display"
                  />
                </div>
                <a href="#">Peças</a>
              </li>
              <div class="division"></div>

              <li>
                <div class="img-center">
                  <img
                    src="../../public/images/imgIcons/icon-ferramentas.jpg"
                    alt=""
                    class="display"
                  />
                </div>
                <a href="#">Máquinas e Ferramentas</a>
              </li>
              <div class="division"></div>

              <li>
                <div class="img-center">
                  <img
                    src="../../public/images/imgIcons/icon-natal.jpg"
                    alt=""
                    class="display"
                  />
                </div>
                <a href="#">Natal</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>
    <div class="nav-categorie eletro">
      home/ <span class="laranja"> Eletrodomésticos </span>
    </div>
    <div class="categorie">
      <div class="categorie-center">
        <img src="../../public/images/destaque-topo.png" alt="" />

        <div></div>
        <div class="categorie-eletro">
          <h1 class="bold laranja" style="font-size: 22px">Eletrodomésticos</h1>
          <input type="checkbox" class="read-more-state" id="post-1" />

          <p class="read-more-wrap">
            Você consegue imaginar sua rotina sem os eletrodomésticos? Difícil,
            né? Eles são equipamentos essenciais para realizar as tarefas
            domésticas com praticidade e eficiência, além de oferecer conforto
            para o seu lar. Aqui na Dufrio você encontra diversas opções de
            eletrodomésticos para a cozinha, a lavanderia e outros ambientes da
            casa.
            <span class="bold"
              >Confira as nossas dicas de compra de eletrodomésticos na Dufrio!
            </span>
            <span class="read-more-target">
              Quando o assunto é eletrodoméstico, o que não falta é a variedade
              de equipamentos para facilitar sua vida em diversos aspectos. São
              aparelhos que te ajudam no dia a dia a cozinhar, lavar louça,
              lavar roupas, secar, conservar, esquentar e refrigerar alimentos,
              entre muitas outras funções. Veja só:
            </span>
          </p>

          <label for="post-1" class="read-more-trigger"></label>
        </div>
      </div>
    </div>
    <div class="line"></div>
    <div class="margin end">
      <div class="itens">
        <label for="">Itens Por pagina: </label>
        <select id="" class="selected-height">
          <option value="" selected>12</option>
          <option value="">teste</option>
          <option value="">teste</option>
          <option value="">teste</option>
        </select>
      </div>

      <div class="ordenar">
        <label for="">Ordenar por: </label>
        <select id="" class="selected-height">
          <option value="" selected>Popularidade</option>
          <option value="">teste</option>
          <option value="">teste</option>
          <option value="">teste</option>
        </select>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "PrimeiroComponente",
};
</script>

<style scoped>
.index1 {
  background-color: var(--orange-defaut);
  width: 100%;
}
.header-width,
.nav-categorie {
  max-width: 1280px;
  margin: 0 auto;
  font-weight: normal;
  justify-content: space-around;
}
.eletro {
  margin-top: 8px;
  margin-bottom: 8px;
}

.nav {
}

.select-btn {
  width: 200px;
  display: flex;
  overflow: hidden;
  background: #fff;
  padding: 24px;
  font-size: 20px;
  font-weight: 400;
  align-items: center;
  cursor: pointer;
  justify-content: space-between;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
}

.options {
  position: absolute;
  width: 300px;
  overflow: auto;
  max-height: 295px;
  padding: 10px;
  margin-top: 10px;
  border-radius: 8px;
  background: #fff;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  display: none;
  animation: fadeInDown 0.35s both;
}

.options .option {
  display: flex;
  height: 55px;
  cursor: pointer;
  padding: 0 16px;
  border-radius: 8px;
  align-items: center;
  background: #fff;
}

.options .option:hover {
  background: #f2f2f2;
}

.options .option .option-text {
  font-size: 18px;
  color: #333;
}

.select-btn svg {
  height: 24px;
  width: 24px;
  transition: 0.2s;
}

.active .select-btn svg {
  transform: rotate(180deg);
}

.active .options {
  display: block;
  opacity: 0;
  z-index: 10;
  animation: fadeInUp 0.4s both;
}

ol {
  list-style-type: none;
  padding: 5px;
  font-size: 13px;
}
ol > li {
  float: left;
  width: 100px;
}
ol > li > ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
  display: none;
}
 
ol > li:hover > ul {
  display: block;
}
ol a {
  color: var(--orange-defaut);
  font-weight: bold;
}
 
ul {
  list-style: none;
}
nav ul li a {
  text-decoration: none;
  color: #c0bdbd;
  
}
.menu1 a{
  font-weight: 100;
}

.menu1 ul {
  display: flex;
  gap: 10px;
  flex-direction: row;
  flex-wrap: wrap;
  padding: 15px;
}
.menu ul li {
}
.menu1 a {
  padding: 15px;
}

.division {
  background-color: #066cb5;
  height: 50px;
  width: 2px;
}
.header-width {
  display: flex;
}

.categorie {
  height: 270px;
  width: 100%;
  background-color: #eff5f7;
}

.categorie-center {
  margin: 0 auto;
  max-width: 1200px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
}

.categorie-eletro {
  display: flex;
  flex-direction: column;
}

.categorie p {
  text-align: justify;
  width: 600px;
}
.categorie-center img {
  margin-top: 20px;
}
.bold {
  font-weight: bold;
}
.line {
  height: 2px;
  width: 100%;
  background-color: #3b7cc9;
}
.orange {
  color: var(--orange-defaut);
  font-weight: bold;
  flex-direction: column;
}
.laranja {
  color: var(--orange-defaut);
}
.center a {
  text-decoration: underline;
}
.center a {
  color: #000;
}

.search {
  width: 50%;
  position: relative;
  display: flex;
  margin-top: 5px;
}

.searchTerm {
  width: 85%;
  border: 2px solid #cacaca;
  border-right: none;
  padding: 5px;
  height: 38.5px;
  border-radius: 5px 0 0 5px;
  outline: none;
  position: relative;
}

.searchButton {
  width: 0px;
  height: 40px;
  cursor: pointer;
  font-size: 20px;
}

.busca {
  width: 40px;
  height: 40px;
  text-align: center;
  border-radius: 0 5px 5px 0;
  cursor: pointer;
  font-size: 20px;
  margin: 0;
  display: inline;
}
.display {
  display: block;
}
.img-center {
  display: flex;
  justify-content: center;
}
div .margin {
  height: 90px;
}
.margin {
  margin: 0 auto;
  max-width: 1200px;
}
.end {
  display: flex;
  justify-content: end;
  align-items: center;
}
/*Ordenar*/
.ordenar {
  margin: 10px;
}
.itens {
  margin: 10px;
}
.selected-height {
  height: 40px;
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 5px;
}

.read-more-state {
  display: none;
}

.read-more-target {
  opacity: 0;
  max-height: 0;
  font-size: 0;
}

.read-more-state:checked ~ .read-more-wrap .read-more-target {
  opacity: 1;
  font-size: inherit;
  max-height: 999em;
}

.read-more-state ~ .read-more-trigger:before {
  content: "Leia mais >";
}

.read-more-state:checked ~ .read-more-trigger:before {
  content: "Leia Menos";
}

.read-more-trigger {
  cursor: pointer;
  display: inline-block;

  color: var(--orange-defaut);
  font-size: 0.9em;

  border: none;
}

@media screen and (max-width: 1288px) {
  .menu1 {
    display: none;
  }
  .menu {
    margin-left: 0;
  }
  .header-width {
    justify-content: flex-start;
  }
}
@media screen and (max-width: 978px) {
  .t {
    display: none;
  }
}
@media screen and (max-width: 694px) {
  .t1 {
    display: none;
  }
  .header-width {
    display: block;
  }
}
@media screen and (max-width: 680px) {
  .categorie-eletro {
    max-width: 200px;
    margin-bottom: 1100px;
  }
  .select-menu {
    background: #fff;
    border: none;
  }
}
.ul-menu li a{
  font-weight: 300;
  color :#fff;
  ;
}
</style>
