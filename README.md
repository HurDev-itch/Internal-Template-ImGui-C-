# ImGui Internal Menu Template for C++ (UE5) 🎮
https://img.shields.io/badge/license-MIT-green
Template éducative pour créer un menu interne ImGui en C++ pour les jeux Unreal Engine 5 (UE5).
⚠️ À but éducatif uniquement – conçu pour apprendre la création de menus internes et la manipulation d’UI dans les jeux.

📸 Aperçu

Exemple de menu interne ImGui avec sliders, boutons et checkboxes.

⚡ Fonctionnalités

Menu interne basique en C++ et ImGui

Widgets de base : boutons, sliders, checkboxes

Démo de menu modulable pour l’éducation

Compatible UE5 (adaptation nécessaire pour d’autres moteurs ou jeux)

🚀 Installation

Cloner le dépôt :

git clone https://github.com/votre-utilisateur/ImGuiInternalMenuTemplate.git

Ajouter ImGui à votre projet :

Téléchargez ImGui depuis le dépôt officiel

Inclure les fichiers sources : imgui.cpp, imgui_draw.cpp, imgui_tables.cpp, imgui_widgets.cpp, imgui_demo.cpp

Ajouter Menu.h et Menu.cpp dans votre projet C++ ou UE5.

🛠 Utilisation

Inclure et appeler le menu dans votre boucle de rendu :

#include "Menu.h"

void RenderGameUI() {
    ImGui::NewFrame();
    
    Menu::Render(); // Affiche le menu interne
    
    ImGui::Render();
}

⚠️ La logique d’affichage de la fenêtre peut nécessiter des adaptations pour certains moteurs ou jeux qui n’utilisent pas UE5.

🎨 Personnalisation

Ajouter vos propres widgets dans Menu.cpp

Modifier les couleurs et styles via ImGui

Adapter la logique de rendu pour d’autres moteurs de jeu

📚 À propos de l’usage

Éducatif : conçu pour apprendre et expérimenter

Non destiné à la distribution ou au hack de jeux commerciaux

Utilisable dans vos projets personnels ou tutoriels

🤝 Contribuer

Ajouter des widgets ou thèmes ImGui

Proposer des correctifs pour compatibilité avec d’autres moteurs

Améliorer la documentation ou exemples de code

📦 Build avec UE5

Créez un projet C++ UE5

Inclure ImGui (vous pouvez utiliser le plugin officiel ImGui for UE5
)

Ajouter Menu.cpp et Menu.h

Appeler Menu::Render() dans votre boucle Tick ou HUD::DrawHUD()

📝 Licence

MIT License – utilisation libre pour projets éducatifs.
Voir le fichier LICENSE
 pour plus de détails.
