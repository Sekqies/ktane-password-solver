# ktane-password-solver
Simple HTML page that helps solve the password module in "Keep Talking and Nobody Explodes"

## Installation
If you have git installed, run
```git
git clone https://github.com/Sekqies/ktane-password-solver
```
Otherwise, click in Code > Download Zip and then extract

## Important note
By default, this program supports the Brazilian Portuguese wordlist. If you wish to change it, go to Line 31 in a text editor of your choosing, and modify this variable to fit your language:
```js
    const wordlist = [
      "acesa", "ajuda", "amigo", "antes", "arcos",
      "baile", "balas", "bispo", "chefe", "cheio",
      "cinto", "cravo", "etapa", "etnia", "flora",
      "lazer", "legal", "lugar", "parte", "parto",
      "perto", "porta", "regra", "resto", "salve",
      "sente", "setor", "sexta", "tecla", "tinta",
      "torta", "touro", "trato", "valer", "veado"
    ];
```

## Usage
Input each possible letter your operator gives you into the correspoding field. You should input each letter without any separator, in lowercase (a,b,c,d,e) -> abcde
If, for instance, your operator says the possible letters for the first position is "V,E,O,A,K,H", you should input as follows in your side:
<img width="1412" height="500" alt="image" src="https://github.com/user-attachments/assets/bb9e3943-f6e6-48c9-9464-fe803e27ec89" />
It will show you all possible words starting with this. If you add that the fourth spot has possible letters "N,M,G,S,B,Z", it will narrow down the possibilites for you as well:
<img width="1255" height="468" alt="image" src="https://github.com/user-attachments/assets/2cb7e8f1-f6eb-4947-a682-3b444a078b45" />
Then, whoever is playing with you can input one of the possible passwords:
<img width="496" height="463" alt="image" src="https://github.com/user-attachments/assets/c490a3e6-1141-491e-ac92-4a3c81adf8b0" />
This confirms one of the words, "Acesa" ("ON" in portuguese), is correct!

If you want to clear the contents of each field, press the "Clear" button



