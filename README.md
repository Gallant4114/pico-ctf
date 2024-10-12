# PicoCTF Write Up

***

## WebDecode
#### Category: Web Exploitation
#### Difficulty: Easy

1. First step, you must run the instance on the challenge. You will see a hyperlink that can be opened to go to a website.
2. You will see the web display below

![image](https://github.com/user-attachments/assets/fb502d6a-4c8d-43bc-91c1-d84987e7fcf4)

3. Try to look at the about tab

![image](https://github.com/user-attachments/assets/819fa462-751d-496c-9e3b-d8ef8a20b991)

4. Inspect the elemen here. Click `ctrl + shift + i` or `fn + f12`. You will see random text here.
   Text `cGljb-10NURnt3ZWJfc3VjYzNzc2Z1bGx5X2QzYzBkZWRfMjgzZTYyZmV9`

![image](https://github.com/user-attachments/assets/ffbed78c-e6f2-4ccc-97fc-38c7dfc56a52)
![image](https://github.com/user-attachments/assets/8bd45a4a-52bc-4eef-97e1-b945b160df7a)

5. Copy the text and decode it!

![image](https://github.com/user-attachments/assets/1ac2cd28-a129-4347-9c37-fc8601e43b2e)

Flag: `picoCTF{web_succ3ssfully_d3c0ded_283e62fe}`

***

## Unminify
#### Category: Web Exploitation
#### Difficulty: Easy

1. Run the instance on this challenge
2. Follow the hyperlink and you wil open a website

![image](https://github.com/user-attachments/assets/a10ceded-34de-45f4-8f1b-930793c70d11)

3. Inspect the element with `ctrl + shift + i` or `fn + f12`

![image](https://github.com/user-attachments/assets/9a2f1450-1b7c-4af6-8e08-9ea55a3c2d79)
![image](https://github.com/user-attachments/assets/e2743f82-1698-4cde-b8b9-b290c770b9d4)

4. You find the flag.

Flag: `picoCTF{pr3tty_c0d3_51d374f0}`
