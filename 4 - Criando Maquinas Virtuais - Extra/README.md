# ☁️ Criando uma Máquina Virtual no Azure ☁️

Esse é o meu resumo de como criar uma **Máquina Virtual (VM)** no **Azure**. Eu anotei os principais passos de forma simples e direta, para quem quiser criar sua própria VM. Vamos lá? 🚀

## Passo a Passo

### 1. Acesse o Portal do Azure 🔗
- Entre no [Portal do Azure](https://portal.azure.com/) com sua conta.
- Na barra de pesquisa, digite **"Máquinas Virtuais"** e clique na opção de **Máquinas Virtuais**.

### 2. Criar uma Nova Máquina Virtual 💻
- Clique em **+ Criar** e selecione **Máquina Virtual**.
- Escolha a **Assinatura** e o **Grupo de Recursos** (ou crie um novo, se necessário).

### 3. Configurar as Informações Básicas 📋
- **Nome da VM**: Escolha um nome para sua máquina.
- **Região**: Defina a região onde sua VM será hospedada (quanto mais perto, melhor a performance).
- **Opção de Disponibilidade**: Selecione um modelo de alta disponibilidade (opcional).
- **Imagem**: Selecione o sistema operacional, como **Windows** ou **Linux**.
- **Tamanho da VM**: Defina o tamanho conforme suas necessidades (CPU e memória).

### 4. Configurar a Conta de Acesso 🔐
- **Nome de Usuário**: Defina o nome do usuário para acessar a VM.
- **Autenticação**: Escolha entre **Senha** ou **Chave SSH** (para Linux).
- **Portas**: Ative a **porta RDP (3389)** para Windows ou **porta SSH (22)** para Linux.

### 5. Configurar o Disco de Armazenamento 💾
- Escolha o tipo de disco (SSD padrão, SSD premium, ou HDD). Recomendo SSD Premium para produção!
- Adicione discos adicionais, se precisar.

### 6. Configurar as Redes 🌐
- O Azure cria automaticamente uma **Rede Virtual (VNet)**, se você não tiver uma.
- Configure o **Endereço IP Público** e o **Grupo de Segurança de Rede (NSG)** para definir as regras de firewall.

### 7. Revisar e Criar ✅
- Após ajustar as configurações, clique em **Revisar e Criar**.
- Verifique as configurações e, se estiver tudo certo, clique em **Criar**!

### 8. Acessar a Máquina Virtual 🎉
- Assim que a VM estiver criada, você poderá acessá-la pelo portal do Azure.
- Para Windows, use **Remote Desktop (RDP)**. Para Linux, conecte via **SSH**.

## 🎯 Dicas Finais

- 💡 Não se esqueça de revisar as opções de segurança e rede!
- 🔧 Quer mais detalhes? O [Guia Oficial do Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/) é um ótimo recurso.

---

## Primeira VM Criada
Bom, seguindo esses passos eu consegui criar minha primeira VM! Dá Só uma olhada...

![image](https://github.com/user-attachments/assets/7fe2d847-5cc0-43c2-860a-ee2a540cfaa7)

![image](https://github.com/user-attachments/assets/332963d6-c209-4a6d-a340-d447769b5c4d)


## 🙏 Agradecimentos e Sugestões
Muito obrigado por conferir meu resumo! Espero que tenha ajudado você a criar sua máquina virtual no Azure. Fique à vontade para sugerir melhorias ou fazer perguntas abrindo uma **issue** ou **pull request**. 😄

🔗 **Entre em contato comigo**:
- [Meu Perfil no GitHub](https://github.com/Rafasansouza)
- [Documentação Oficial do Azure](https://docs.microsoft.com/en-us/azure/)

---

✨ **Happy Coding!** ✨
