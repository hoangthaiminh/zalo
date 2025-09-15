# My Zalo profile
___My Zalo profile, edited version of [@longathelstan](https://github.com/longathelstan/zalo/) and Zalo___

**Live Preview: [*Here*](https://minabsoci.ct.ws/)**

-------

## Make it your own:
- Edit at **\<head\>** tag
  - Edit content displayed on social networks:
    - [ ] **Description**
    - [ ] **og:title** *(Your title displayed)*
    - [ ] **og:description** *(Same as **Description** above)*
    - [ ] **og:image** *(Icon displayed next to title)*
  - Edit content displayed on the browser:
    - [ ] Edit at **\<title\>** tag *(This item will display the title on the browser)*
  - ***(More: You can edit some things in the \<style\> tag to your own style)***
- Edit at **\<body\>** tag
  - Edit the content displayed on the header bar:
    - [ ] Edit the small avatar displayed on the left side of the header bar according to your Zalo avatar
    - [ ] Edit the small avatar displayed on the right side of the header bar according to the Zalo avatar of a contributor to your project
    - ***(You can change the order of avatar display according to your needs)***
  - Edit the content displayed on the footer bar:
    - [ ] Edit the content in the footer tag as needed. Note that the footer tag can contain different text formatting styles such as:
      - **Bold** (Using: \<b\>Your bold content\<\/b\>)
      - *Italic* (Using: \<i\>Your italic content\<\/i\>)
      - <ins>underline</ins> (Using: \<u\>Your underline content\<\/u\>)
      - You can even *insert links* by: \<a href\=\'Your link\'\>Description for your link\<\/a\>
    - Example using:
      - Display: "Look at me, I can **bold**, *italicize* or <ins>underline</ins> as I like. [You can click on me!](https://example.com/)"
      - Code: "**Look at me, I can \<b\>bold\<\/b\>, \<i\>italicize\<\/i\> or \<u\>underline\<\/u\> as I like. \<a href\=\'your-link-here.com\'\>You can click on me!\<\/a\>**"
- Edit at **\<script\>** tag
  - Edit the contents in 'window.pageInfo':
    - [ ] **name**: Your Zalo account name
    - [ ] **avatar**: Your Zalo avatar image link
    - [ ] **thumbnail**: Your thumbnail displayed when sharing
    - [ ] **description**: Description of your Zalo account (*bio*)
    - [ ] **qrCodeUrl**: Your Zalo QR code image link
    - [ ] **background**: Your Zalo cover photo
    - In the '**user**' section:
      - [ ] **isBusiness**: Change this from **false** to **true** if your account is a business account
    - In the '**messageInfo**' section (🎯 ***Important***):
      - [ ] **argv**: Your Zalo phone number
      - [ ] **convId**: Change this if you have your Zalo chat login session, otherwise leave it blank
  - Edit in "**async function animateText()**" section:
    - [ ] Replace "**<Type text line 1>**" with the text you want to automatically type the first time
    - [ ] Replace "**<Type text line 2>**" with the text you want to automatically type the second time
    - [ ] ... (**Add more cyclical structured paragraphs like the two lines above if you want to automatically type more**)
    - (***We recommend that your auto-typed text be no longer than 25 characters per line to avoid exceeding visibility***)
