# Instalação do sistema  

## Como instalar o Sistema MentorSoft.
Nesse passo a passo, estaremos ensinando a como fazer a instalação do sistema em uma máquina qualquer.  
Para continuar, precisaremos de acesso ao servidor.  

Você deve:  
> Mapear Unidade de Rede para a pasta do sistema utilizando a letra K.  
Após a conclusão do mapeamento, ao acessar o mapeamento (K:\) deve encontrar as pastas  
>> - Backup  
>> - DLL  
>> - EXE  

![1](/img/instalacao-sistemas/1.png)  

No seu C:\ crie uma pasta chamada **MentorSoft** , dentro dessa pasta deve ficar da seguinte forma:  
> Backup – Pasta padrão de backup do sistema  
> EXE – Executáveis do sistema  
>> - MentorSoft.exe  
>> - sisKM.ini  
> DLL - Para o sistema funcionar

Vá no servidor (K:\) em **K:\exe** copie os arquivos **MentorSoft.exe** e **sisKM.ini** e cole em **C:\MentorSoft\exe**;  
Logo em seguida vá em **K:\DLL** copie todos os arquivos e cole em **C:\MentorSoft\exe** e **C:\MentorSoft\dll**:  

Se o usuário que utilizará máquina for responsável de backup, você precisa configurar a mesma para que o faça, vá em **K:\Backup**, copie todos os arquivos que não contenham a extensão **.backup** e cole em **C:\MentorSoft\Backup**

Okay, seu sistema está instalado e deve funcionar, vá na pasta **C:\MentorSoft\exe** e crie um atalho do **MentorSoft.exe**.  
