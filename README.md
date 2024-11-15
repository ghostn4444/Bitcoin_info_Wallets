# Carteiras de Bitcoin sem KYC, com Auto-custódia e sem necessidade de baixar a Blockchain

Este repositório contém uma lista de **10 carteiras de Bitcoin** que atendem aos seguintes critérios:
- **Auto-custódia**: Você mantém o controle completo sobre suas chaves privadas.
- **Sem KYC (Know Your Customer)**: Não é necessário fornecer informações pessoais para usar a carteira.
- **Sem necessidade de baixar a blockchain completa**: As carteiras não exigem que você baixe a blockchain inteira para fazer transações, economizando espaço no seu dispositivo.

| **Carteira**           | **Auto-custódia** | **Sem KYC** | **Sem necessidade de baixar a blockchain completa** | **Anonimato / Privacidade**               | **Plataforma**        |
|------------------------|-------------------|-------------|---------------------------------------------------|-------------------------------------------|-----------------------|
| **Electrum**            | Sim               | Sim         | Sim (conecta a servidores externos)               | Bom (com Tor)                             | Windows, macOS, Linux |
| **Wasabi Wallet**       | Sim               | Sim         | Sim (conecta a servidores externos)               | Muito bom (CoinJoin + Tor)                | Windows, macOS, Linux |
| **Blockstream Green**   | Sim               | Sim         | Sim (conecta a servidores Blockstream)            | Bom (com Tor)                             | Windows, macOS, Linux |
| **Samourai Wallet**     | Sim               | Sim         | Sim (conecta a servidores externos)               | Muito bom (CoinJoin + Tor)                | Android (emulador no PC) |
| **BlueWallet**          | Sim               | Sim         | Sim (conecta a servidores externos)               | Moderado                                  | Windows, macOS, Linux |
| **Exodus**              | Sim               | Sim         | Sim (conecta a servidores externos)               | Moderado                                  | Windows, macOS, Linux |
| **Armory**              | Sim               | Sim         | Não (exige baixar a blockchain completa)          | Moderado                                  | Windows, macOS, Linux |
| **Bitcoin Core**        | Sim               | Sim         | Não (exige baixar a blockchain completa)          | Moderado                                  | Windows, macOS, Linux |
| **Jaxx Liberty**        | Sim               | Sim         | Sim (conecta a servidores externos)               | Moderado                                  | Windows, macOS, Linux |
| **Coinomi**             | Sim               | Sim         | Sim (conecta a servidores externos)               | Moderado                                  | Windows, macOS, Linux |

## Descrição das Carteiras

### 1. **Electrum**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores externos)
- **Anonimato / Privacidade**: Bom (com Tor)
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Electrum é uma carteira leve, rápida e segura. Oferece recursos como **multisig**, **transações offline** e pode ser configurada para usar **Tor** para aumentar o anonimato. É uma das carteiras mais confiáveis no ecossistema Bitcoin.

### 2. **Wasabi Wallet**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores externos)
- **Anonimato / Privacidade**: Muito bom (CoinJoin + Tor)
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Wasabi Wallet é focada em **privacidade** e **anonimato**. Ela utiliza **CoinJoin** para misturar transações, dificultando o rastreamento, e oferece integração com **Tor** para proteger seu IP. É uma das melhores opções para quem prioriza anonimato.

### 3. **Blockstream Green**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores Blockstream)
- **Anonimato / Privacidade**: Bom (com Tor)
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Blockstream Green é uma carteira com forte foco em segurança, oferecendo **multisig** e autenticação de dois fatores (2FA). Ela também suporta a configuração de **Tor** para ocultar seu IP, aumentando a privacidade.

### 4. **Samourai Wallet** (via emulador Android para desktop)
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores externos)
- **Anonimato / Privacidade**: Muito bom (CoinJoin + Tor)
- **Plataforma**: Android (pode ser usado no PC via emulador)
- **Descrição**: Samourai Wallet é uma das carteiras mais privadas, com recursos como **CoinJoin**, **Stonewall** e **Tor** para ocultação de IP. A carteira é nativa para Android, mas pode ser usada no PC através de um emulador.

### 5. **BlueWallet**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores externos)
- **Anonimato / Privacidade**: Moderado
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: BlueWallet é uma carteira intuitiva que oferece suporte à **Lightning Network** e Bitcoin regular. Embora ofereça controle sobre suas chaves privadas, não possui as mesmas funcionalidades de privacidade avançadas como Wasabi ou Samourai.

### 6. **Exodus**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores externos)
- **Anonimato / Privacidade**: Moderado
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Exodus oferece uma interface amigável e suporte para múltiplas criptomoedas. A carteira permite o controle das chaves privadas e a segurança básica, mas não é especializada em privacidade.

### 7. **Armory**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Não (exige baixar a blockchain completa)
- **Anonimato / Privacidade**: Moderado
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Armory é uma carteira altamente segura, com suporte a **multisig** e **transações offline**. Ela requer o download completo da blockchain, o que oferece total controle sobre as transações, mas exige mais espaço e recursos.

### 8. **Bitcoin Core**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Não (exige baixar a blockchain completa)
- **Anonimato / Privacidade**: Moderado
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Bitcoin Core é o cliente oficial do Bitcoin, com segurança máxima, pois valida todas as transações por conta própria. No entanto, ele exige o download completo da blockchain, o que pode ser um obstáculo para quem não tem muito espaço ou largura de banda.

### 9. **Jaxx Liberty**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores externos)
- **Anonimato / Privacidade**: Moderado
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Jaxx Liberty é uma carteira multi-cripto que oferece fácil controle sobre suas chaves privadas e suporta várias criptomoedas, incluindo Bitcoin. No entanto, sua privacidade não é tão forte quanto outras carteiras mais focadas, como Wasabi.

### 10. **Coinomi**
- **Auto-custódia**: Sim
- **Sem KYC**: Sim
- **Sem necessidade de baixar a blockchain completa**: Sim (conecta a servidores externos)
- **Anonimato / Privacidade**: Moderado
- **Plataforma**: Windows, macOS, Linux
- **Descrição**: Coinomi é uma carteira multi-cripto que oferece controle completo sobre suas chaves privadas e suporte para várias criptomoedas. Embora não seja especializada em privacidade, é uma boa opção para quem busca praticidade e segurança.

## Conclusão

Se você está buscando uma carteira de Bitcoin com **auto-custódia**, **sem KYC** e **sem a necessidade de baixar a blockchain completa**, as opções acima são todas excelentes, dependendo das suas necessidades de **privacidade** e **facilidade de uso**.

- **Para privacidade e anonimato avançados**: **Wasabi Wallet**, **Samourai Wallet** (via emulador), **Electrum** (com Tor).
- **Para segurança e facilidade de uso**: **Exodus**, **BlueWallet**, **Jaxx Liberty**, **Coinomi**.
- **Para segurança máxima** (mas exige mais espaço e recursos): **Bitcoin Core**, **Armory**.

Escolha a que melhor atende às suas necessidades e comece a usar o Bitcoin com maior controle e segurança.
