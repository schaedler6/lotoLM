<<<<<<< HEAD
# lotoLM — versão ML (one-class)

- Treina **somente com dados reais** (cole concursos no campo de texto da página).
- Modelo client-side em **TensorFlow.js** (autoencoder one-class).
- Interpretação: **MSE baixo** = mais próximo do histórico (não é previsão).

Abra a página (após habilitar o Pages): https://schaedler6.github.io/lotoLM/
=======
# lotoLM — dados reais automáticos

- A página lê **data/draws.txt** ao abrir (mesma origem).
- Workflow **update-draws.yml** atualiza o arquivo diariamente a partir de \DATA_SOURCE_URL\ (secret).
- Treino: autoencoder one-class (TensorFlow.js). **Não é previsão**, é ranqueamento por semelhança (MSE).

URL (após Pages): https://schaedler6.github.io/lotoLM/
>>>>>>> 0153373 (feat: index com auto-carregamento + workflow de atualização diária)
