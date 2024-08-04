<!DOCTYPE html>
<html>

 <link rel="stylesheet" href="styles.css">
<body>
    <h1>Análise Exploratória de Dados: Empresa Loggi</h1>
    <img src="images/project1_1.jpeg" alt="Uma bela paisagem" width="900" height="500" title="Clique para ampliar">
    <h2>1.0 Introdução ao problema de neǵocios</h2>
     <h3>1.1 Metas e objetivos</h3>
    <p>O projeto de análise exploratória de dados foi realizado para a empresa Loggi, uma startup brasileira de logística. O objetivo foi entender e otimizar os desafios logísticos enfrentados pela empresa, com foco em rotas de entrega e a alocação de pedidos em veículos com capacidade limitada.
     Os dados estão disponibilizados no github através do <a href="https://github.com/loggi/loggibud" target="_blank">(link)</a> com dados e códigos para problemas típicos que empresas de logística enfrentam: 
</p>
 <h2>2. Dados </h2>
 <h3>2.1 Coleta</h3> Vamos trabalhar com um sub conjunto dos dados originais presentes neste <a href="https://github.com/loggi/loggibud">(link)</a>. Em especial, consolidei em um único arquivo JSON as instâncias de treino de cvrp da cidade de Brasília.
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
<h2>3. Resultados</h2>
<h3>3.1 Insights da Análise Exploratória em Python</h3>
<p> 
<ul>
  <li><P><b>Identificação de Áreas de Alta Demanda:</b></P></li>
<P><b>Insight:</b><b> Regiões df-0, df-1 e df-2</b> cidades como Brasília, Taguatinga, Asa Norte, e Águas Claras têm o maior número de entregas.</P>
<P><b>Ação:</b> Focar em otimizar as operações nessas áreas de alta demanda, alocando mais recursos, como veículos e pessoal, para garantir entregas mais rápidas e eficientes.</P>

<P><li><b>Planejamento de Recursos:</b></P></li>
<P><b>Insight:</b> A diferença no número de entregas entre as cidades e bairros sugere que a alocação de recursos pode ser ajustada para melhor atender à demanda.</P>
<P><b>Ação:</b> Redistribuir a frota de veículos e a alocação de motoristas com base na demanda específica de cada cidade e bairro. Isso ajudará a evitar a subutilização ou sobrecarga de recursos em determinadas áreas.</P>

<P><li><b>Oportunidades de Expansão:</b></P></li>
<P><b>Insight:</b> Cidades e bairros com um número significativo de entregas, mas que não estão no topo da lista, podem representar oportunidades de crescimento.</P>
<P><b>Ação:</b> Investigar essas áreas para entender melhor as necessidades dos clientes e considerar a expansão dos serviços ou a abertura de novos hubs para atender melhor essas áreas.</P>

<P><li><b>Eficiência Operacional:</b></P></li>
<P><b>Insight:</b> Analisar a eficiência das entregas nas áreas de maior demanda pode revelar oportunidades de melhoria.
<P><b>Ação:</b> Implementar tecnologias de otimização de rotas e monitoramento em tempo real para melhorar a eficiência das entregas. Isso pode incluir o uso de algoritmos de roteamento e sistemas de gestão de transporte (TMS).</P>

<P><li><b>Utilização da Capacidade dos Veículos:</b></P></li>
<P><b>Insight:</b> A análise da capacidade dos veículos em relação ao tamanho das entregas mostrou que há uma correlação positiva, indicando uma utilização eficiente dos veículos.
<P><b>Ação:</b> Continuar monitorando a utilização dos veículos para garantir que eles estejam sendo usados de maneira eficiente. Ajustar a alocação de pedidos para maximizar a capacidade dos veículos pode ajudar a reduzir custos operacionais.

<P><li><b>Satisfação do Cliente:</b></P></li>
<P><b>Insight:</b> Áreas com alta demanda de entregas são críticas para a satisfação do cliente.<P>
<P><b>Ação:</b> Garantir que as entregas nessas áreas sejam rápidas e confiáveis. Implementar sistemas de feedback do cliente para monitorar a satisfação e resolver problemas rapidamente.
</p>
  
<h2>4. Ferramentas utilizadas</h2>
<img src="images/img_python.svg" alt="Uma bela paisagem" width="75" height="25" title="img_python">
<img src="images/img_VScode.svg" alt="Uma bela paisagem" width="75" height="25" title="img_VScode">
<img src="images/img_jupyter.svg" alt="Uma bela paisagem" width="75" height="25" title="img_jupyter">
<h3>4.1 Bilbliotecas Python utilizadas</h3>
<img src="images/img_pandas.svg" alt="Uma bela paisagem" width="75" height="25" title="img_pandas">
<img src="images/img_matplotlib.svg" alt="Uma bela paisagem" width="75" height="25" title="img_matplotlib">
<img src="images/img_seaborn.svg" alt="Uma bela paisagem" width="75" height="25" title="Clique para ampliar">
<img src="images/img_numpy.svg" alt="Uma bela paisagem" width="75" height="25" title="img_numpy">
<img src="images/img_geopandas.png" alt="Uma bela paisagem" width="75" height="25" title="img_numpy">



</body>
</html>
