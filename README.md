# Template de App Android com Jetpack Compose

Este repositório serve como um template para projetos Android. Ele utiliza a SDK 35, Material Design 3 e Jetpack Compose, oferecendo uma base sólida para o desenvolvimento de aplicativos modernos.

## Como usar

1. **Criar um repositório a partir do template:**

   Clique no botão "Use this template" no GitHub para criar um novo repositório a partir deste template. Dê um nome descritivo ao seu repositório.

2. **Clonar o repositório:**

   ```bash
   git clone <URL_DO_SEU_REPOSITORIO>
   ```

3. **Abrir no Android Studio:**

   Abra o projeto clonado no Android Studio.

4. **Configurar o projeto:**

    * **`settings.gradle.kts`:**  Verifique se o nome do projeto e o nome do módulo estão corretos e correspondem à sua estrutura de projeto.
    * **`build.gradle.kts` (Módulo app):**
        * Modifique o `applicationId` para o ID único do seu aplicativo (ex: `com.example.meuapp`).
        * Verifique as dependências e adicione ou remova conforme necessário para o seu projeto.
    * **`AndroidManifest.xml`:**
        * Atualize o nome do pacote para corresponder ao seu `applicationId`.
        * Configure permissões necessárias para o seu aplicativo.

5. **Executar o aplicativo:**

   Compile e execute o aplicativo em um emulador ou dispositivo físico.

## Boas práticas

Este template inclui algumas boas práticas para desenvolvimento Android:

* **Jetpack Compose:** UI declarativa moderna.
* **Material Design 3:**  Componentes e estilos visuais atualizados.
* **Arquitetura recomendada:** Implemente uma arquitetura adequada (MVVM, MVI, etc.) à medida que seu projeto evolui.

## Recursos adicionais

* [Documentação do Android](https://developer.android.com/docs)
* [Jetpack Compose](https://developer.android.com/jetpack/compose)
* [Material Design 3](https://m3.material.io/)

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.


## Licença

[MIT](LICENSE)