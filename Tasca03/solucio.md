# T03 - Seguretat Lògica: Recuperant accés a sistemes  
**Autor:** Jan Fernández Paulinelli  

---

## Manual per Recuperar Password en Ubuntu

### Procediment individual

1. **Vulnereu l’accés al GRUB del Linux.**

<img width="771" height="569" alt="Captura de pantalla 2025-10-14 190119" src="https://github.com/user-attachments/assets/55b2458e-3d06-446f-82b5-6c244e1f740f" />

<img width="780" height="478" alt="Captura de pantalla 2025-10-14 190235" src="https://github.com/user-attachments/assets/f04c9c2c-5f60-4803-9fcb-e396f0850579" />

<img width="771" height="429" alt="Captura de pantalla 2025-10-14 190441" src="https://github.com/user-attachments/assets/dea9795b-3d91-4846-87db-bbc6d17e0b1e" />

2. **Identifiqueu l’usuari del sistema.**

<img width="518" height="36" alt="Captura de pantalla 2025-10-14 190829" src="https://github.com/user-attachments/assets/2a1fb7c0-de92-4c52-ae2a-9bf123bc6298" />

3. **Modifiqueu la contrasenya de l’usuari i verifiqueu que ara ja té accés.**  

<img width="266" height="14" alt="Captura de pantalla 2025-10-14 191115" src="https://github.com/user-attachments/assets/c7cb9bb3-f297-43cc-94b9-272c50c2981d" />

   - **Contrasenya nova:** `Usuari`

<img width="394" height="16" alt="Captura de pantalla 2025-10-14 191136" src="https://github.com/user-attachments/assets/9966a8c9-aaf5-4ec7-8d19-58f8ff270726" />

5. **Investigueu com es pot fortificar l’accés al GRUB.**  És molt important que indiquis les fonts d’informació que utilitzis.

<img width="642" height="132" alt="Captura de pantalla 2025-10-16 184817" src="https://github.com/user-attachments/assets/d525f769-72a9-4ac1-a844-d76dec81e1a8" />

<img width="641" height="129" alt="Captura de pantalla 2025-10-16 184902" src="https://github.com/user-attachments/assets/6d5e0f32-e938-4789-82bc-2a4f2652aaa3" />

<img width="418" height="25" alt="Captura de pantalla 2025-10-16 184958" src="https://github.com/user-attachments/assets/4ebe3748-3334-48a4-8165-24ce4da21ca4" />

1. Dins del fitxer, premeu `Ctrl + R` i introduïu aquesta comanda.

<img width="489" height="31" alt="Captura de pantalla 2025-10-16 185132" src="https://github.com/user-attachments/assets/a1c9e21a-b37c-4c77-a695-fb2e538d4ea0" />

**Font d’informació:**  
[Protegiendo GRUB en Ubuntu Server - WayToIT](https://waytoit.wordpress.com/2019/09/15/protegiendo-grub-en-ubuntu-server/)

---

2. Un cop dins, obriu l’aplicació de l’editor de textos.

<img width="722" height="791" alt="Captura de pantalla 2025-10-16 185423" src="https://github.com/user-attachments/assets/f1fe2315-4356-4dc9-9878-f13f8c8194a3" />

3. Obriu els dos documents següents:

- `40_custom`
- `salida.txt`

<img width="1274" height="758" alt="Captura de pantalla 2025-10-16 190110" src="https://github.com/user-attachments/assets/a76cbfb7-394d-4ca3-9fba-78ed37f315b1" />

5. Afegiu la informació del tutorial i la contrasenya amb hash al document `40_custom`.

<img width="892" height="430" alt="Captura de pantalla 2025-10-16 191734" src="https://github.com/user-attachments/assets/4534f858-0dac-43c4-ae95-084672c873df" />

6. Tanqueu l’editor de textos i introduïu la comanda següent per aplicar la configuració del GRUB.

<img width="627" height="294" alt="Captura de pantalla 2025-10-16 192401" src="https://github.com/user-attachments/assets/51da0139-f7cf-4636-aa30-7ceb2286adc1" />

> **Nota:** Assegureu-vos que el fitxer `40_custom` s’ha actualitzat correctament abans de regenerar el GRUB.



