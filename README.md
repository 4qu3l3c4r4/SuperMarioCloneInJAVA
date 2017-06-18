Super Mario Bros. Clone
==========
![image](logo.png)

Um clone do jogo Super Mario Bros. na versão 16 bits.

** NOTA: ** Os recursos originais foram substituídos!

### Sobre
Este jogo é baseado na versão do Super Mario Bros. 16 bits apresentada no Super Mario All-Starts para o Super Nintendo (SNES). O jogo está escrito em Java e usando o mecanismo [LibGdx](http://libgdx.badlogicgames.com/) engine.

Características do jogo:
* O Mini Mario se transforma em grande Mario com a ajuda de cogumelos.
* Se você cair da plataforma num buraco, você vai morrer.
* Os inimigos matarão Mario, mas Mario pode mata-los saltando em suas cabeças.
* Salte contra tijolos, eles serão destruídos se você for grande.
* Tijolos de bônus que podem conter vários cogumelos.
* No final do nível, você pode deslizar para baixo da bandeira, então você caminhará automaticamente para o castelo. O jogo reiniciará.

### Demo video

[![Youtube video](http://img.youtube.com/vi/GxyUYAL4O7I/0.jpg)](http://www.youtube.com/watch?v=GxyUYAL4O7I)

### Configuração de desenvolvimento

Usando o IntelliJ:

1. Instale Java JDK. Verifique se JAVA_HOME está em suas variáveis ​​de ambiente.
2. Instale o SDK do Android e configure uma plataforma Android. Certifique-se de configurar ANDROID_HOME em suas variáveis ​​de ambiente.
3. Instale o Gradle.
3. Clone este repositório. Abra o projeto em seu IDE.
Se você estiver usando IntlliJ, o plugin Gradle deve ser instalado por padrão. As configurações do projeto gradle devem aparecer.
Aceite as configurações padrão. Se falta o Android SDK ou JAVA_HOME certifique-se de configurar Java e Android SDK em suas variáveis ​​de ambiente.
4. Edite sua configuração de execução. Certifique-se de que o `android/assets` esteja configurado como seu diretório de trabalho!
5. Quando executado no IntelliJ, ele deve compilar automaticamente.
