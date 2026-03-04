# ₿ NitroGen — Bitcoin Cold Wallet
**Air-gapped · BIP39 · BIP84 · PSBT Signer**

NitroGen é uma carteira de Bitcoin focada em soberania e segurança. Ela foi projetada para rodar em ambientes **100% offline (air-gapped)**, permitindo gerar sementes (*seeds*), endereços e assinar transações sem nunca tocar na internet.

---

## ⬇️ Download

Você pode baixar a versão mais recente pronta para uso na seção oficial de lançamentos:
> **[Acessar Releases no GitHub](https://github.com/admdaniel/NitroGen-Cold-Wallet/releases)**

---

## 🚀 Funcionalidades

* **Geração Segura:** Cria mnemônicos (seeds) de 12 ou 24 palavras seguindo o padrão **BIP39**.
* **Segwit Nativo:** Suporte ao padrão **BIP84** (endereços começando com `bc1q`).
* **Carteira de Vigília (Watch-only):** Exportação de **ZPUB** para monitorar saldo em apps como BlueWallet ou Sparrow.
* **Assinador PSBT:** Assine transações offline com verificação de taxas e destinos diretamente na tela.
* **Portátil:** Executável único para Linux x64 (não requer instalação de Node.js).

---

## 🔒 Como usar (Segurança Máxima)

Para garantir a integridade total dos seus fundos, siga este procedimento:

1.  **Preparação:** Baixe o executável e coloque-o em um pendrive limpo.
2.  **Ambiente Isolado:** Use um computador offline (ex: Tails OS ou um Linux com Wi-Fi e Bluetooth fisicamente desligados).
3.  **Execução:**
    Extraia os arquivos, abra o terminal na pasta e execute:
    ```bash
    chmod +x NitroGEN
    ./NitroGEN
    ```
4.  **Backup:** Anote sua **Seed** em papel ou metal. **Nunca** a armazene digitalmente (fotos, nuvem ou arquivos de texto).
5.  **Acompanhamento:** Importe apenas o **ZPUB** no seu celular para acompanhar o saldo e gerar ordens de pagamento com segurança.

---

## ⚠️ Isenção de Responsabilidade

> **Aviso:** Este é um software experimental de código aberto. O uso de chaves privadas envolve riscos significativos. Não utilize para grandes quantias sem antes realizar testes exaustivos de recuperação. O desenvolvedor não se responsabiliza por eventuais perdas de fundos.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.
