![Stochastic](https://github.com/user-attachments/assets/ea028a6a-c957-47f8-bf44-6533cc700a14)

# Tiling Estocastico

Tiling estocastico para evitar la repetición de texturas

## Requisitos

* Unity **6000.3.10f1**
* Render Pipeline: Universal Render Pipeline (URP)
* Paquetes: Visual Effect Graph
* Assets de terceros incluidos (no redistribuibles): AmplifyShaderEditor

## Contenido

* **VFX Graph:** `New VFX`
* **Shader Graph:** `StochasticTest`, `TileStochastic_TileWithOutRepetition`
* **Sub Graphs:** `Stochastic`, `TileStochastic_Hash23`, `TileStochastic_SubGraph`, `TileStochastic_UVRandomTransform`, `TileStochastic_UVTransform`
* **Shaders HLSL:** `Stochastic`, `TileStochastic_RepetitionASE`
* **Escenas:** `Assets/3-Scenes/Main.unity`, `Assets/3-Scenes/scene.unity`

## Uso

1. Clona el repositorio y añádelo en Unity Hub (*Add project from disk*).
2. Ábrelo con Unity **6000.3.10f1**.
3. Abre la escena `Assets/3-Scenes/Main.unity` y pulsa **Play**.
