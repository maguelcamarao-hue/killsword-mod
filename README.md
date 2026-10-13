# Kill Sword (Fabric, Minecraft 1.21.1)

Espada que mata qualquer mob com um unico golpe. Nao quebra, e jogadores sao poupados por padrao.

- Minecraft Java **1.21.1**
- Fabric Loader (>= 0.19.5) + **Fabric API** para 1.21.1
- Java **21**

## Como compilar

1. Instale o JDK 21.
2. Abra um terminal nesta pasta e rode:
   - Windows: `gradlew.bat build`
   - Linux/Mac: `./gradlew build`
3. O mod fica em `build/libs/killsword-1.0.0.jar` (NAO use o arquivo `-sources`).
4. Copie esse .jar para a pasta `mods` do Minecraft (junto com o Fabric API).

## Como obter a espada

- Criativo: aba **Combate**, ou `/give @s killsword:kill_sword`
- Sobrevivencia: receita (coluna vertical) com Estrela do Nether, Espada de Netherite, Estrela do Nether.

## Ajustes rapidos

Em `src/main/java/com/killsword/KillSwordItem.java`:
- `KILLS_PLAYERS = true` faz a espada matar jogadores tambem.
- O dano base da espada fica em `SwordItem.createAttributes(...)`.

## Licenca

CC0-1.0
