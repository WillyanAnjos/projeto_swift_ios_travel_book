📍 TravelBook – iOS Study Project

TravelBook é um aplicativo iOS desenvolvido em Swift com o objetivo de registrar e visualizar lugares visitados em um mapa.
O projeto demonstra conceitos fundamentais do desenvolvimento iOS, incluindo MapKit, CoreLocation, CoreData e UIKit.

A aplicação permite que o usuário marque locais no mapa, adicione informações e salve esses dados localmente, criando uma lista persistente de lugares favoritos.

Este projeto foi criado como estudo prático para consolidar conceitos essenciais da plataforma iOS e demonstrar habilidades importantes para a posição de iOS Developer.

🚀 Funcionalidades
📍 Marcar locais no mapa

O usuário pode pressionar o mapa por alguns segundos para selecionar um ponto geográfico.
Após selecionar o local, é possível adicionar:

Nome do lugar

Comentário ou descrição

Esse ponto é exibido no mapa através de um Map Annotation (MKPointAnnotation).

💾 Persistência de dados com CoreData

Todos os locais adicionados são salvos utilizando CoreData, incluindo:

Nome

Descrição

Latitude

Longitude

Identificador único (UUID)

Isso garante que os dados permaneçam salvos mesmo após fechar o aplicativo.

📋 Lista de lugares salvos

A tela principal apresenta uma lista de locais armazenados utilizando UITableView.

O usuário pode:

Visualizar os lugares cadastrados

Selecionar um lugar para visualizar no mapa

Remover lugares da lista

🗺️ Visualização no mapa

Ao selecionar um local da lista, o aplicativo:

Busca os dados no CoreData

Centraliza o mapa na localização salva

Exibe um marcador com nome e descrição

🧭 Abrir rota no Apple Maps

Ao tocar no botão de detalhes do marcador, o aplicativo abre o Apple Maps com a opção de navegação até o local selecionado.

🧠 Conceitos iOS demonstrados no projeto

Este projeto explora vários conceitos importantes para desenvolvimento iOS:

📱 UIKit

UIViewController

UITableView

NavigationController

Segues entre telas

Gesture Recognizers

🗺️ MapKit

MKMapView

MKAnnotation

MKMarkerAnnotationView

Integração com Apple Maps

📍 CoreLocation

Permissões de localização

Atualização da posição do usuário

Centralização do mapa baseada na localização atual

💾 CoreData

Persistência local

FetchRequest

Predicates

CRUD de dados

🔔 Comunicação entre telas

Uso de NotificationCenter para atualizar a lista quando um novo local é salvo.

📲 Fluxo da aplicação

1️⃣ O usuário abre o aplicativo e vê a lista de lugares salvos
2️⃣ Pressiona o botão "+" para adicionar um novo local
3️⃣ Pressiona o mapa por alguns segundos para marcar uma localização
4️⃣ Adiciona nome e comentário
5️⃣ Salva o local
6️⃣ O local aparece na lista principal
7️⃣ Ao selecionar o item, o mapa mostra a localização salva

🛠️ Tecnologias utilizadas

Swift

UIKit

MapKit

CoreLocation

CoreData

Xcode

🎯 Objetivo do projeto

Este projeto foi desenvolvido para praticar conceitos fundamentais do ecossistema iOS e demonstrar conhecimento em:

Persistência de dados

Manipulação de mapas

Gerenciamento de localização

Navegação entre telas

Arquitetura básica de apps iOS
