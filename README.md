# Documentação criada com o intuito de explicar o processo de instalação do sistema operacional Oracle Linux 8.6 na VMBox.  
  obs: O Oracle Linux se trata de um sistema operacional sem interface gráfica (apenas terminal).  
    
## Processo de instalação da VMBox.
  
### 1- Vamos no link: https://www.virtualbox.org/wiki/Downloads.  
![image](https://user-images.githubusercontent.com/103605697/191844876-ff5c386e-9608-4e6c-ae25-336abe20ea5a.png)  
  
Clique no SEU sistema operacional em "VirtualBox 6.1.38 platform packages".   
  
    
### 2- Após baixado, clique no executável, onde aparecerá em sua tela:  
![image](https://user-images.githubusercontent.com/103605697/191845795-48437fc3-f014-484a-bb41-8ba690974345.png)  
  
Clique em "Next" > "Next" > "Next" > "Yes" > "Install".  
Finalizado o processo de instalação, sua VMBox estará pronta para uso. :)  
  
     
## Processo de instalação do sistema operacional Oracle Linux 8.6 na VMBox.  
    
### 1- Vamos no link: https://yum.oracle.com/oracle-linux-isos.html.  
Onde iremos baixar a imagem do Oracle Linux.  
![image](https://user-images.githubusercontent.com/103605697/191847603-6e10fcdb-a5f5-498e-8123-0b793d151ef9.png)  
   
Clique no link que se refere a "Full ISO" na "Release: 8.6".  
     
     
     
### 2- Finalizado a instalação da ISO, vamos abrir a VMBox e clicar em "New" para que uma nova máquina virtual seja criada:  
![image](https://user-images.githubusercontent.com/103605697/191847084-4f1fd060-31f8-47f6-b9fc-71b06de12058.png)  
     
         
     
### 3- Selecionamos "Name: Nome_de_sua_preferencia" > "Type: Linux" > "Version: Oracle(64bits)" > "Next".   
![image](https://user-images.githubusercontent.com/103605697/191848796-66791b88-5e7a-4890-a2e0-8b2e138555e7.png)  
    
      
    
### 4- Hora de configurar sua máquina virtual.
  Escolha o tamanho da sua memória RAM da sua máquina:  
![image](https://user-images.githubusercontent.com/103605697/191849308-8045b711-5ae3-46a9-a8dc-dfc6f8d33f42.png)
     
          
  Escolha se irá criar o disco rígido (recomendado criar um disco rígido virtual para que não comprometa o disco rígido da sua máquina).  
![image](https://user-images.githubusercontent.com/103605697/191849403-66071c78-46ca-49c4-9f70-bd22786dfadc.png)   
   
    
  Selecione o "VHD" criando assim um disco virtual.   
![image](https://user-images.githubusercontent.com/103605697/191850718-d0f96ce3-3691-4ed8-a166-23840c06c97d.png)  
    
       
  Selecione o "Dynamically allocated" criando assim o armazenamento do seu disco de forma dinamica.
![image](https://user-images.githubusercontent.com/103605697/191850863-670bd7d3-4d65-418b-a03e-5738eba79f7d.png)   
  
    
  Selecione a Pasta e o Tamanho da sua máquina virtual (recomendado manter as configurações).  
![image](https://user-images.githubusercontent.com/103605697/191850974-5720f4ee-1e2e-424c-b293-d16c6d194f0a.png)  
  
     
Você poderá ver que sua máquina virtual já aparece em sua VMBox: :)   
![image](https://user-images.githubusercontent.com/103605697/191851579-5414d4ab-77f0-4fca-8fdc-b0c61ecbb5ff.png)  

    
  
### 5- Agora iremos iniciar a instalação da imagem Oracle.  
  Clique em sua máquina virtual e em seguida em "Start" para que ela inicie:    
![image](https://user-images.githubusercontent.com/103605697/191852094-71f1005b-5b1d-419c-9753-dcbce16f78de.png)   
   
  Clique na pasta amerela:  
![image](https://user-images.githubusercontent.com/103605697/191852490-d1c64cca-a51a-4224-845b-15ac97d0a03d.png)   
  
  Clique em "Add" > Selecione a imagem ISO baixada anteriormente > "Choose" > "Start":   
![image](https://user-images.githubusercontent.com/103605697/191852553-eac8781f-2c1b-40ed-8ce9-60e2c5dbea37.png)  
   
  Clique em "Install Oracle Linux 8.6":   
![image](https://user-images.githubusercontent.com/103605697/191852883-327b1582-db63-4bd0-80b7-e530c2ae309b.png)   
  
  
### 6- Vamos configurar a sua máquina virtual.  
  Escolha a língua da sua máquina (recomendado ser o Inglês):  
![image](https://user-images.githubusercontent.com/103605697/191854009-5cfd969d-9ec9-46c5-bb17-c12c1df76e92.png)  
  
  Escolha seu Teclado em "Keyboard" > Data e hora em "Time & Date" > Senha do seu usuário root em "Root Password" > Crie (não obrigatório) usuário e senha em "Create Account":   
![image](https://user-images.githubusercontent.com/103605697/191854931-8deb84d3-e606-4146-b089-c690be416474.png)  
   
  Escolha em "Software Selection: Minimal Install" para que seja feito a instalação somente do terminal.  
![image](https://user-images.githubusercontent.com/103605697/191854894-799a0d9e-da3c-416b-870f-9de211335ae8.png)   
  
  Para ativar a intenet vá em "Netword & Host Name" e coloque em modo ativo em "On":  
![image](https://user-images.githubusercontent.com/103605697/191855285-8a0c2ae0-47be-42fd-925d-0e5cee50d59e.png)  
  
  Selecione o seu discon em "Installation Destination":  
![image](https://user-images.githubusercontent.com/103605697/191855203-6af80b9f-7730-488c-a678-6ce3622d0917.png)  
    
  Finalizado as configurações! Clique em "Begin Installation":   
![image](https://user-images.githubusercontent.com/103605697/191855865-6d351c7b-cc23-4dd2-bc18-25f4fafe8703.png)    
     
  Onde iniciará o processo de instalação:    
![image](https://user-images.githubusercontent.com/103605697/191855955-435d838a-e186-4d1e-8a86-7d00f93d88a4.png)    
  
  Finalizado o processo de instalação clique em "Reboot System" para reiniciar seu sistema:
![image](https://user-images.githubusercontent.com/103605697/191864417-484e8412-4f47-40da-892d-b8466b765f7e.png)

      
        
Pronto! Agora é só entrar com seu login e senha!    
  
    
## E não se esqueça!    
Em seu terminal dê o comando: 

                  dnf update
para atualizar os pacotes de seu sitema. :D  
