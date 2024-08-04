<!DOCTYPE html>
<html>

 <link rel="stylesheet" href="styles.css">
<body>
    <h1>Análise Exploratória de Dados: Empresa Loggi</h1>
    <img src="images/project1_1.jpeg" alt="Uma bela paisagem" width="900" height="500" title="Clique para ampliar">
    <h2>Introdução ao problema de neǵocios</h2>
     <h3>Metas e objetivos</h3>
    <p>O projeto de análise exploratória de dados foi realizado para a empresa Loggi, uma startup brasileira de logística. O objetivo foi entender e otimizar os desafios logísticos enfrentados pela empresa, como a com foco em rotas de entrega e a alocação de pedidos em veículos com capacidade limitada.
     Os dados estão disponibilizados no github através do <a href="https://github.com/loggi/loggibud" target="_blank">(link)</a> com dados e códigos para problemas típicos que empresas de logística enfrentam: 
</p>
 <h2>1.Dados </h2>
 <h3>1.1 Coleta</h3> Vamos trabalhar com um sub conjunto dos dados originais presentes neste <a href="https://github.com/loggi/loggibud">(link)</a>. Em especial, consolidei em um único arquivo JSON as instâncias de treino de cvrp da cidade de Brasília.
 O dado bruto é um arquivo do tipo JSON com uma lista de instâncias de entregas. Cada instância representa um conjunto de entregas que devem ser realizadas pelos veículos do hub regional. Exemplo:</h3>
<img src="images/dado_brutojson_.png" alt="Uma bela paisagem" width="900" height="500" title="Clique para ampliar">
 <p>Onde:</p>
    <ul>
        <li><strong>name:</strong> uma string com o nome único da instância;</li>
        <li><strong>region:</strong> uma string com o nome único da região do hub;</li>
        <li><strong>origin:</strong> um dict com a latitude e longitude da região do hub;</li>
        <li><strong>vehicle_capacity:</strong> um int com a soma da capacidade de carga dos veículos do hub;</li>
        <li><strong>deliveries:</strong> uma list de dict com as entregas que devem ser realizadas.</li>
    </ul>
  <p>Sendo que:</p>
    <ul>
        <li><strong>id:</strong> uma string com o id único da entrega;</li>
        <li><strong>point:</strong> um dict com a latitude e longitude da entrega;</li>
        <li><strong>size:</strong> um int com o tamanho ou a carga que a entrega ocupa no veículo.</li>
    </ul> 
<h2>Resultados</h2>
 
<h3>Insights da Análise Exploratória</h3>
  <p> 
  Relatório de Análise Exploratória - Loggi

    <h1>Identificação de Áreas de Alta Demanda</h1>
    <p><strong>Regiões df-0, df-1 e df-2:</strong> Cidades como Brasília, Taguatinga, Asa Norte, e Águas Claras têm o maior número de entregas. <br>
    <strong>Ação:</strong> Focar em otimizar as operações nessas áreas de alta demanda, alocando mais recursos, como veículos e pessoal, para garantir entregas mais rápidas e eficientes.</p>

    <h2>Planejamento de Recursos</h2>
    <p><strong>Insight:</strong> A diferença no número de entregas entre as cidades e bairros sugere que a alocação de recursos pode ser ajustada para melhor atender à demanda. <br>
    <strong>Ação:</strong> Redistribuir a frota de veículos e a alocação de motoristas com base na demanda específica de cada cidade e bairro. Isso ajudará a evitar a subutilização ou sobrecarga de recursos em determinadas áreas.</p>

    <h2>Oportunidades de Expansão</h2>
    <h2>Eficiência Operacional</h2>
    <h2>Utilização da Capacidade dos Veículos</h2>
    <h2>Satisfação do Cliente</h2>
    <h2>Conclusão</h2>
    <p>Os insights extraídos deste projeto fornecem uma base sólida para otimizar as operações logísticas da Loggi. Ao focar em áreas de alta demanda, ajustar a alocação de recursos, explorar oportunidades de expansão e melhorar a eficiência operacional, a empresa pode aumentar sua eficiência e satisfação do cliente, resultando em um aumento no faturamento.</p>


  
  
  </p>
<h2>Ferramentas utilizadas</h2>
</body>
</html>
