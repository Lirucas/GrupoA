<style>
/* Remove completamente a sidebar */
.md-sidebar, .md-sidebar--primary {
    display: none !important;
}

.md-main {
    margin-left: 0 !important;
}

/* Fundo da Página Inicial */
.md-main::before {
    content: "";
    background: url('assets/fundo.jpg') no-repeat center center fixed;
    background-size: cover;
    opacity: 0.3;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
}

/* Estilização do conteúdo */
.home-content {
    text-align: center;
    color: #000;
    padding: 20px 20px 10px; /* Reduz a margem superior */
    font-size: 180%;
    font-weight: bold;
    margin-top: -40px; /* Eleva todo o conjunto para cima */
}

.home-content h1 {
    font-size: 180%;
    font-weight: bold;
    margin-bottom: 2px;
}

.home-content h2 {
    font-size: 160%;
    font-weight: bold;
    margin-top: -5px; /* Reduz o espaço entre o título e os blocos */
}

/* Estilo dos blocos de membros */
.membros-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
    margin-top: 10px; /* Reduz ainda mais a distância do topo */
}

.membro-card {
    background: rgba(255, 255, 255, 0.8);
    border-radius: 10px;
    padding: 10px;
    width: 28%;
    text-align: center;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

/* Responsividade */
@media (max-width: 800px) {
    .membro-card {
        width: 45%;
    }
}

@media (max-width: 500px) {
    .membro-card {
        width: 90%;
    }
}
</style>

<div class="home-content">
    <h1>✈️ Grupo A</h1>
    <h2>Urban Air Mobility</h2>
    <p><strong>São José dos Campos - SP</strong></p>    
</div>

<div class="membros-container">

    <div class="membro-card">
        <h3>Lucas Lira Sassett</h3>
        <p><strong>Nível:</strong> Mestrado</p>
        <p><strong>Programa:</strong> EAM 1</p>
        <p><strong>Formação:</strong> Engenharia Aeroespacial</p>
    </div>

    <div class="membro-card">
        <h3>Alex Sandro Mendes Tostes</h3>
        <p><strong>Nível:</strong> Doutorado</p>
        <p><strong>Programa:</strong> CTE E</p>
        <p><strong>Formação:</strong> Engenharia Mecânica</p>
    </div>

    <div class="membro-card">
        <h3>Edson A. A. Guedes Filho</h3>
        <p><strong>Nível:</strong> Doutorado</p>
        <p><strong>Programa:</strong> EIA T</p>
        <p><strong>Formação:</strong> Ciências Jurídicas</p>
    </div>

<div class="membro-card">
        <h3>Francisco H. Figueiredo Araújo</h3>
        <p><strong>Nível:</strong> Mestrado</p>
        <p><strong>Programa:</strong> CTE E</p>
        <p><strong>Formação:</strong> Engenharia Eletrônica</p>
    </div>

    <div class="membro-card">
        <h3>Gabriela Oliveira de Souza</h3>
        <p><strong>Nível:</strong> Doutorado</p>
        <p><strong>Programa:</strong> EIA T</p>
        <p><strong>Formação:</strong> Arquitetura e Urbanismo</p>
    </div>

</div>
