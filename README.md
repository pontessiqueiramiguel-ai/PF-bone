# Prehistoric Fauna Bonemeal Plants (addon)

Addon separado para Prehistoric Fauna (Forge 1.20.1). Usar bonemeal nas plantas abaixo faz elas dropparem o item,
igual ao girassol. Plantas altas dropam a versão baixa.

Altas -> versão baixa: tall_horsetail, tall_osmunda, tall_osmundacaulis, tall_otozamites, tall_taeniopteris,
tall_fiddlehead_fern, tall_archaefructus

Dropam a si mesmas: dead_osmundacaulis, callianthus, azolla, cobbania, nelumbo, quereuxia, algae_carpet,
stoneworts, moss_carpet, ptilophyllum_base

Para adicionar/remover plantas, edite o mapa em `BonemealHandler.java` (ids de bloco -> ids de item).

Build: `./gradlew build` -> jar em `build/libs/`. Coloque na pasta `mods` junto com o Prehistoric Fauna.
