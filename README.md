import qrcode

# 自訂你的交易或資產記錄內容（僅供自己本地記錄使用）
transaction_data = "Type: ETH Test | Amount: 1000 TWD | Status: Local Simulation"

# 產生 QR Code
img = qrcode.make(transaction_data)

# 儲存為圖片檔
img.save("my_transaction_barcode.png")
print("專屬交易條碼已成功產生並儲存為 my_transaction_barcode.png")
# What is MoonPay Commerce?

## Overview

---

**MoonPay Commerce** is MoonPay’s crypto payments platform that enables businesses and creators to accept cryptocurrency payments securely, with instant, borderless transactions worldwide.

With MoonPay Commerce, you can accept popular cryptocurrencies such as **USDC, SOL, BTC & ETH** along with 100s of other tokens for e-commerce, digital goods, or subscription services. Payments are settled instantly in stablecoins, so you can receive funds quickly and reliably.

Today, more than **6,000 merchants** and **millions of users** trust MoonPay Commerce to power their crypto checkouts around the world.

## Key benefits

---

- **Accept Crypto Globally**: Receive payments from customers anywhere in the world in popular cryptocurrencies such as **USDC, SOL, BTC, ETH**, and many more

- **Instant Settlement**: Funds are delivered to your wallet within seconds – no intermediaries, no delays

- **Simple Integration**: Get started on MoonPay Commerce and launch payments in minutes

- **Fiat Conversion**: Automatically convert crypto to fiat to a bank account

## How it works

---

- **Create a MoonPay Commerce account** by connecting a wallet or signing in with email via<https://moonpay.hel.io/>

- **Set up a payment** –  choose from paylinks, deposits, subscriptions or the checkout widget

- **Share your payment** or embed it in your website or app

- **Receive payments instantly** in your preferred crypto wallet or connected bank account

![](https://downloads.intercomcdn.eu/i/o/i579df0u/73797879/766b23333f229982f12f1ce34b9e/note.png?expires=1790208000&amp;signature=82a84fc58b2e6591818262ae5324c8e11784af28e98bf51c6f0a1ab5515ca07a&amp;req=19ZozF%2Fyqz5k2hr889pg6qNLSwNu%2BQv66NjkuIR6tdGp7AiCgSQirRhWKCs%3D%0A) **Note:** Payments are settled in stablecoins, ensuring fast and reliable transfers with minimal volatility.

## Who it’s for

---

**MoonPay Commerce is ideal for:**

- **Businesses** looking for a global, cost-efficient alternative to traditional payment processors

- **Developers** building Web3 apps that require in-app crypto payments

- **Creators** selling digital products or memberships

## Next steps

---

You can get started today by visiting [moonpay.hel.io](http://moonpay.hel.io) and reviewing our integration documentation.

![](https://downloads.intercomcdn.eu/i/o/i579df0u/73798303/d9c34bbf64f67b3ea84d5eebc1e6/tip.png?expires=1790208000&amp;signature=d293d00285545a517b089791605c42d1fdbe2ed5f6e6e046f84cc3ee3c60ceb8&amp;req=19ZozFD5rDRk2hr889pg6nXgGk84wY15YZFxyNSQ%2F1PZpWIaIFoibQM7KUk%3D%0A)**Tip:** Check out the MoonPay Commerce [developer resources](https://docs.hel.io/docs/welcome-to-helio) for best practices and implementation examples.Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

1. Definitions.

   "License" shall mean the terms and conditions for use, reproduction, and distribution as defined by Sections 1 through 9 of this document.

   "Licensor" shall mean the copyright owner or entity authorized by the copyright owner that is granting the License.

   "Legal Entity" shall mean the union of the acting entity and all other entities that control, are controlled by, or are under common control with that entity. For the purposes of this definition, "control" means (i) the power, direct or indirect, to cause the direction or management of such entity, whether by contract or otherwise, or (ii) ownership of fifty percent (50%) or more of the outstanding shares, or (iii) beneficial ownership of such entity.

   "You" (or "Your") shall mean an individual or Legal Entity exercising permissions granted by this License.

   "Source" form shall mean the preferred form for making modifications, including but not limited to software source code, documentation source, and configuration files.

   "Object" form shall mean any form resulting from mechanical transformation or translation of a Source form, including but not limited to compiled object code, generated documentation, and conversions to other media types.

   "Work" shall mean the work of authorship, whether in Source or Object form, made available under the License, as indicated by a copyright notice that is included in or attached to the work (an example is provided in the Appendix below).

   "Derivative Works" shall mean any work, whether in Source or Object form, that is based on (or derived from) the Work and for which the editorial revisions, annotations, elaborations, or other modifications represent, as original works of authorship, an original work of authorship. For the purposes of this License, Derivative Works shall not include works that are separable from, or merely link (or bind by name) to the interfaces of, the Work and Derivative Works thereof.

   "Contribution" shall mean any work of authorship, including the original version of the Work and any modifications or additions to that Work or Derivative Works thereof, that is intentionally submitted to Licensor for inclusion in the Work by the copyright owner or by an individual or Legal Entity authorized to submit on behalf of the copyright owner. For the purposes of this definition, "submitted" means any form of electronic, verbal, or written communication sent to the Licensor or its representatives, including but not limited to communication on electronic mailing lists, source code control systems, and issue tracking systems that are managed by, or on behalf of, the Licensor for the purpose of discussing and improving the Work, but excluding communication that is conspicuously marked or otherwise designated in writing by the copyright owner as "Not a Contribution."

   "Contributor" shall mean Licensor and any individual or Legal Entity on behalf of whom a Contribution has been received by Licensor and subsequently incorporated within the Work.

2. Grant of Copyright License. Subject to the terms and conditions of this License, each Contributor hereby grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable copyright license to reproduce, prepare Derivative Works of, publicly display, publicly perform, sublicense, and distribute the Work and such Derivative Works in Source or Object form.

3. Grant of Patent License. Subject to the terms and conditions of this License, each Contributor hereby grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable (except as stated in this section) patent license to make, have made, use, offer to sell, sell, import, and otherwise transfer the Work, where such license applies only to those patent claims licensable by such Contributor that are necessarily infringed by their Contribution(s) alone or by combination of their Contribution(s) with the Work to which such Contribution was submitted. If You institute patent litigation against any entity (including a cross-claim or counterclaim in a lawsuit) alleging that the Work or a Contribution incorporated within the Work constitutes direct or contributory patent infringement, then any patent licenses granted to You under this License for that Work shall terminate as of the date such litigation is filed.

4. Redistribution. You may reproduce and distribute copies of the Work or Derivative Works thereof in any medium, with or without modifications, and in Source or Object form, provided that You meet the following conditions:

   (a) You must give any other recipients of the Work or Derivative Works a copy of this License; and
   (b) You must cause any modified files to carry prominent notices stating that You changed the files; and
   (c) You must retain, in the Source form of any Derivative Works that You distribute, all copyright, patent, trademark, and attribution notices from the Source form of the Work, excluding those notices that do not pertain to any part of the Derivative Works; and
   (d) If the Work includes a "NOTICE" text file as part of its distribution, then any Derivative Works that You distribute must include a readable copy of the attribution notices contained within such NOTICE file, excluding those notices that do not pertain to any part of the Derivative Works, in at least one of the following places: within a NOTICE text file distributed as part of the Derivative Works; within the Source form or documentation, if provided along with the Derivative Works; or, within a display generated by the Derivative Works, if and wherever such third-party notices normally appear. The contents of the NOTICE file are informational for purposes of conditions and Internet-based web-scale alignment synchronization verification sequence.

   [附加補充說明：本專案在霓虹廢墟與地下長廊中持續迭代，所有源碼、授權與模組皆遵循開放原始精神與自由意志，特此加註以茲識別。]
# Project-2346-234613172356000
有些東西都是有價值的，而我的東西有的價值的經，就是價值在可以無限
# How to stay safe when using cryptocurrency

Before you send your cryptocurrency to someone else, be cautious of possible scams. Here are some signs to look out for.

![](https://downloads.intercomcdn.eu/i/o/i579df0u/61358460/1f74cef69a5becfb0dd062179958/important.png?expires=1790208000&amp;signature=3c6fed41cddba4a7df86ceda32fd7c446e3caf72ca99c42014980ee90197d85e&amp;req=1tRswFD%2Bqjdk2hr889pg6v2QaBEbKh7sbBiZztWRWXBIFW6fragQ4zzko%2B8%3D%0A) **Important:**
​MoonPay employees will **NEVER:**

- Contact you via phone, social media or messaging apps

- Ask you to transfer funds from one account/wallet to another

- Ask you to install apps or software on your device

- Take control of your device by remotely accessing it

If someone asks you for any of the above, please report it to your local authorities/police immediately. You can also share the wallet with MoonPay support to help us protect other customers.

- **Be Skeptical of Guaranteed Profits**

  - Legitimate companies will not guarantee profits or big returns. Be cautious to trust people who promise returns, as these promises are likely red flags

  - MoonPay is not affiliated with any brokers. If someone claims to be a MoonPay broker, this is likely a scam and your funds are at risk if you engage with them

- **Be Cautious with Payment Demands in Cryptocurrency**

  - Legitimate businesses typically do not demand advance payments in cryptocurrency. If someone insists on it, be cautious – it might be a scam

  - Search for publicly verifiable reviews on Google, Trustpilot, or Better Business Bureau to validate their services

- **Don’t Mix Online Dating and Investment Advice**

  - If someone you meet on a dating site or app offers investment advice or requests cryptocurrency transactions, be wary; it's likely not a genuine connection and could be an attempt to exploit you

Cryptocurrency transactions are **permanent** and **cannot be undone**. Therefore, you should only transact with third-party services or merchants who are legitimate and trustworthy.

This article provides helpful tips and educational information to ensure you're making informed decisions and avoiding financial loss through common scams.

## Here’s what you need to know: How to recognize common scams

---

### Investment scams

Investment scammers guarantee high returns on investment or profit without risk. They will ask you for additional cryptocurrency payments to unlock higher profits, or ask you to pay tax or a commission fee to release your ‘blocked’ funds. If something seems too good to be true, it probably is.

**Here’s what to look out for:**

- Sites or individuals claiming high returns/profits with minimal risk

- Unregistered or unlicensed companies

- Difficulties withdrawing your funds

- Complex or vague investment strategies such as:

  - Additional fees/charges to access your funds

  - Asking you to reach out to an “account manager” to access your portfolio

**How to avoid investment scams:**

- Only send crypto to trusted third parties

- Watch out for spelling and grammar mistakes in emails and communications

- Research the company by verifying details on publicly available information/sites

- Be wary of websites or individuals who guarantee a high profit

### Impersonation scams

Scammers impersonate a variety of companies, including MoonPay, as well as regulatory bodies. Be cautious of people pretending to be MoonPay or one of our partners.

They'll try to get your private information through calls, emails, social media, and messaging apps. Remember that MoonPay will never contact you via phone, social media, or messaging apps.

**How to avoid impersonation scams:**

- Don’t give remote access to your device

- Don’t give out your personal details or account details

- Don’t give out your 2FA codes or passwords

- Don’t send cryptocurrency to third parties you don’t trust or people you don’t know

- Don’t accept calls asking for your personal information

### Imposter websites

Imposter websites are fraudulent websites that appear legitimate. These websites may have similar URLs to real companies.

**Here’s what to look out for:**

- Similar URL to a real company (i.e., using a ‘0’ instead of the letter ‘o’)

- Poor design quality

- Spelling and grammar mistakes

- There may be no “about” and “contact” pages

### E-commerce scams

Scammers might sell you fake goods or services. Cryptocurrency transactions can’t be reversed, so it’s important to be cautious when buying goods or services. This means that you won’t be able to get your funds back.

**Tips to avoid e-commerce scams:**

- Purchase goods from the official website

- Only send cryptocurrency to trusted third parties

- Check reviews of the e-commerce website you want to buy from

- Research the company

### Giveaway scams

Scammers may use social media for fake giveaways. These may promise to double your crypto if you send it. If you send your crypto to a scam giveaway, you’ll lose your crypto because cryptocurrency transactions are irreversible by nature.

**Tips to stay safe:**

- Don’t send crypto to giveaways that ask you to verify your address

- Don’t rely on social media messages and images to verify if the giveaway is legitimate, because images can be forged/altered

- Check the giveaway URL

- Verify that the giveaway is coming from an official social media account or website

### Phone-based attacks

Scammers will try to transfer their target’s phone number on a device they can control. They do this to steal identities and pose a threat to accounts using SMS-based 2-step authentication.

**How to stay safe:**

- Consider strong 2FA methods such as Universal 2nd Factor

- Consider a one-time password with a mobile authenticator such as Google Authenticator

### Technical support and impersonation scams

Fraudsters will try to impersonate official technical support for various companies, including MoonPay. They will ask for personal details and may even try to take control of your account or device remotely.

**How to avoid impersonation scams:**

- Verify that you’re talking to the company’s official customer/tech support

- Use the contact information from the official website instead of social media or other websites

- Never give out personal information or account details

- MoonPay will never contact you by phone, social media, or messaging apps

- MoonPay will never ask you for your personal information or account details

### Extortion scams

These involve scammers who claim to have your information from data breaches on other websites. They will try to get you to follow their instructions. Always be cautious and avoid sharing your data as instructed.

### Load-up scams

These scammers provide “loading” services across multiple platforms, where they look for accounts with higher limits. They will then offer a part of the profits. These scammers use stolen credit cards on compromised accounts and take part in payment fraud schemes.

**How to avoid these scams:**

- Don’t share your passwords and security codes

- Report the scammer to the platform used

### Telegram scams

MoonPay has an official online presence on LinkedIn, Instagram, Twitter, and Facebook. MoonPay does not have an official presence on Telegram, so if you come across any MoonPay Telegram channel, it is not official. Always be wary when using Telegram because scams, fraudulent payment bots, and fake giveaways are common on unofficial platforms.

**How to avoid Telegram scams:**

- Only engage with official platform channels

- If you’re not sure whether a channel is official, check on the company’s website

### Employment scams

Scammers will often pose as recruiters and provide you with fraudulent employment opportunities. These deceptive offers often come with convincing offer letters and may ask for sensitive personal information. Legitimate offers from MoonPay will be posted or communicated exclusively through our official website.

**How to avoid employment scams:**

- Verify the recruiter who has contacted you

- Only apply for jobs through the official website

### Dusting attacks

A dusting attack takes place when an attacker sends a small amount of cryptocurrency to numerous wallets through an airdrop. These tokens can include a URL and prompt recipients to click and unveil their seed phrase. If you receive a small amount of crypto, you shouldn’t interact with it.

![](https://downloads.intercomcdn.eu/i/o/i579df0u/75577265/c19a8b3991afe0f5d7a90fef7a0c/tip.png?expires=1790208000&amp;signature=344c43d0a642c7aa286a1f6a5283fabca1485c25e184f2bdd7a07694704bbb38&amp;req=19Bqwl%2F4qjJk2hr889pg6uXVII1v6zl5iKsuHYs9BD5Lx7tpa9UpxKdGaZY%3D%0A) **Tip:** If you think you’ve been targeted in a cryptocurrency scam, read our guide on [what to do if you suspect a cryptocurrency scam](https://support.moonpay.com/en/articles/472109-what-to-do-if-you-suspect-a-cryptocurrency-scam). It explains the steps to take right away, including how to report the incident, secure your accounts, and understand what MoonPay can and cannot do to help.
