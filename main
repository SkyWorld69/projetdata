"""Lance l'application
"""


from vue.start import Start


if __name__ == '__main__':

    # on démarre l'application avec une mémoire vide
    memory = {}
    current_vue = Start(memory)

    # tant qu'on a un écran à afficher, on continue
    while current_vue:
        # on affiche une bordure pour séparer les vue
        with open('assets/border.txt', 'r', encoding="utf-8") as asset:
            print(asset.read())
        # le menu agit (demande d'action à effectuer, réalisation de l'action, préparation du prochain menu, ...)
        current_vue = current_vue.run()
