# ₿ NitroGen — Bitcoin Cold Wallet
**Air-gapped · BIP39 · BIP84 · PSBT Signer**

NitroGen é uma carteira de Bitcoin focada em soberania e segurança. Ela foi projetada para rodar em ambientes 100% offline (air-gapped), permitindo gerar sementes (seeds), endereços e assinar transações sem nunca tocar na internet.

## ⬇️ Download

Você pode baixar a versão mais recente pronta para uso na seção **[Releases](https://github.com/admdaniel/NitroGen-Cold-Wallet/releases)**.

## 🚀 Funcionalidades

* **Geração Segura:** Cria mnemônicos (seeds) de 12 ou 24 palavras (BIP39).
* **Segwit Nativo:** Padrão BIP84 (endereços começando com `bc1q`).
* **Relógio de Vigília (Watch-only):** Exportação de ZPUB para monitorar saldo em apps como BlueWallet ou Sparrow.
* **Assinador PSBT:** Assine transações offline com verificação de taxas e destinos na tela.
* **Portátil:** Executável único para Linux x64 (não requer instalação de Node.js).

## 🔒 Como usar (Segurança Máxima)

1. **Baixe o executável** e coloque-o em um pendrive.
2. **Use um computador offline** (ex: Tails OS ou um Linux com Wi-Fi/Bluetooth desligados).
3. **Extraia os arquivos** e execute:

\`\`\`bash
chmod +x NitroGEN
./NitroGEN
\`\`\`

4. **Anote sua Seed** em papel ou metal. Nunca a armazene digitalmente.
5. **Importe o ZPUB** no seu celular para acompanhar o saldo e gerar ordens de pagamento.

## ⚠️ Isenção de Responsabilidade

Este é um software experimental de código aberto. O uso de chaves privadas envolve riscos. Não use para grandes quantias sem antes realizar testes de recuperação. O desenvolvedor não se responsabiliza por perda de fundos.

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo `LICENSE` para detalhes.
