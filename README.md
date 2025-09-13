
<img src = "https://m.media-amazon.com/images/I/71QQQVroZUL._AC_UF350,350_QL80_.jpg" width=350px height=190px align="center"/>

## Team
[Chiara Barone](https://github.com/Chiaaa17)<br>
[Ottavia Biagi](https://github.com/ottavia31)<br>
[Elisabetta Cometti](https://github.com/Betticometti)<br>
[Perla Durante](https://github.com/perladurante)<br>

## Progress

| Functionality | State |
|:-----------------------|:------------------------------------:|
| Basic rules | ![#c5f015](https://placehold.it/15/44bb44/44bb44) |
| Complete rules | ![#c5f015](https://placehold.it/15/44bb44/44bb44) |
| Socket | ![#c5f015](https://placehold.it/15/f03c15/f03c15) |
| RMI | ![#c5f015](https://placehold.it/15/44bb44/44bb44) |
| GUI | ![#c5f015](https://placehold.it/15/f03c15/f03c15) |
| CLI | ![#c5f015](https://placehold.it/15/44bb44/44bb44)|
| Multiple games | ![#c5f015](https://placehold.it/15/f03c15/f03c15) |
| Persistence | ![#c5f015](https://placehold.it/15/f03c15/f03c15) |
| Chat | ![#c5f015](https://placehold.it/15/44bb44/44bb44) |
| Disconnections | ![#c5f015](https://placehold.it/15/f03c15/f03c15) |


## Setup

- In the deliverables folder there are two jar files, one to set the Server up, and the other one to start the Client.
- The Server can be run with the following command:
    ```shell
    > java -jar CodexServer.jar [port] [host]
    ```

- The Client can be run with the following command:
    ```shell
    > java -jar CodexClient.jar [port] [host]
    ```
    This commands have to be followed by this program arguments:
    - **port**: number of the port for the RMI connection
    - **host**: ip addres of the server
    
- To correctly display emojis while running TUI on Windows Terminal, you can use this commands:
    ```shell
    > $OutputEncoding = [System.Console]::OutputEncoding = [System.Console]::InputEncoding = [System.Text.Encoding]::UTF8

    ```
    ```shell
    > $PSDefaultParameterValues['*:Encoding'] = 'utf8'
  
    ```
