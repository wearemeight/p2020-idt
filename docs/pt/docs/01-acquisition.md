## A interface FMS

Os principais fabricantes de camiões acordaram em homogeneizar a ligação de equipamentos desenvolvendo assim uma interface comum entre eles, a ficha FMS.
A interface FMS (Fleet Management System) é a norma que homogeniza o protocolo de comunicação para permitir a abertura ao público, isto é, permitir que empresas terceiras desenvolvam equipamentos periféricos como é o caso de atuadores/sistemas de aquisição de dados para aplicações de condução autónoma, por exemplo.
Os construtores que integram este acordo são Daimler, MAN Truck & Bus, Scania, DAF Trucks, CNH IVECO, Volvo Trucks e Renault Trucks.
Esta norma foi desenvolvida para evitar a ligação direta ao sistema interno de CANBUS do veículo que pode comprometer a integridade e o funcionamento correto do veículo, chegando mesmo em alguns casos a comprometer a garantia do veículo. Assim, a ficha FMS é a única ligação existente para aquisição de dados com segurança sem comprometer o camião.
A informação transmitida por esta ficha respeita o mesmo protocolo e formatação de dados entre todos os veículos para além de ter o mesmo pinout em todos os modelos. Tem também disponíveis canais de potência que permitem a alimentação do equipamento em questão quando conectado a esta ficha.


## Desenvolvimento de Hardware

A necessidade de desenvolver o equipamento deriva da frequência de aquisição de dados dos equipamentos atualmente disponíveis. Uma vez que, atualmente, à data da realização deste projeto, não existe nenhum serviço a fornecer indicações em tempo real ao condutor, nenhum equipamento tem capacidade para fornecer os dados de forma a que o sistema funcione correctamente.
O equipamento desenvolvido tem uma taxa de aquisição de até 4Hz o que permite obter informação detalhada sobre o funcionamento do camião e, após a aplicação dos modelos desenvolvidos fornecer as indicações sobre ações para o motorista optimizar o consumo de combustível, de acordo com a carga transportada.

O equipamento desenvolvido é apresentado na imagem abaixo.

<p align="center">
  <a href="https://www.meight.com"><img src="https://meight-p2020-idt.s3.eu-central-1.amazonaws.com/C2B.png"></a>
</p>


<p align="center">
  <a href="https://www.meight.com"><img src="https://meight-p2020-idt.s3.eu-central-1.amazonaws.com/logos.png" width="400"></a>
</p>