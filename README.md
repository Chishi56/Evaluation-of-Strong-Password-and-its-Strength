# Evaluation-of-Strong-Password-and-its-Strength
## Objective
This Project emphasizes on what makes a password strong and test it against password strength tools.

## Tools Used
[passwordmonster](https://www.passwordmonster.com/)

## Guidelines
Use uppercase, lowercase, numbers, symbols, and length variations.

## Crack Time and Feedback from the tool used

| **Password**        | **Password Strength**                                   | **Time to Crack** |
|---------------------|---------------------------------------------------|------------|
| **vintage**       | Very Weak                     | 0.19 Seconds |
| **Morrison#123**       | Very Weak        | 11.69 Seconds |
| **hashing1**  | Weak               | 13.74 Seconds |
| **Devilmaycry69**         | Medium                   | 9 Hours |
| **Supercalifragilisticexpialidocious**   | Very Strong              | 18 Billion Trillion Years |
| **G$4jF#kL9@mP8!zR2%vN6^qW3&**       | Very Strong              | 2 Billion Billion Trillion Years |
| **Johnny#@69** | Medium                 | 23 Hours |
| **Pneum0n0ultramicr0scopicsilic$volcanoc#ni@sis89856**   | Very Strong | 1 Billion Trillion Trillion Years |


&nbsp;


## Strong & Secure Password Guidelines
### Dont's
- A password should not be a normal word.
- It should not contain only letters.
- Never use your basic personal details that is being exposed to public e.g. Social Media, name of your pet, Car License Plate Number, Hobbies or anything that reveals your identity to the masses.
- Avoid using short passoword and it should not follow a sequential pattern.

### Do's
- Use a mixture of uppercase, lowercase, numbers, symbols, and length variations. However, it should not follow a sequential pattern as shown in the table i.e. Morrison#123, 123 being sequential pattern.
- Password should be as lenghty as possible with uses of uppercase, lowercase, numbers, symbols, and length variations  e.g. G$4jF#kL9@mP8!zR2%vN6^qW3&, which takes 2 Billion Billion Trillion Years making it impossible to crack
- Use a trusted Password Manager to store all of your password securely so that you can retrieve complex password which you cannot remember.
- Use 2 Factor-Authentication for Maximum Security.


  &nbsp;

## Common Password Attacks
- **Phishing:** In this type of attack an adversary can trick a user into revealing password. For instance, sending an email with a link claiming that your password is leak and that it requires immediate action, leading that sent link to a forged website making it look authentic e.g. Instagram login page
- **Brute Force Attack:** Password Cracking Tools like THC-Hydra and John The Ripper can be use for cracking passwords. In this attack a user provides input for the possible combination of password e.g. using your basic details as an input for the tool and based on that provided input it presents all the possible passwords that may have a match to the victims original password.
- **Dictionary:** Same as Brute Force attack but the main difference is, it uses a predfined list of password, you can think of it like an Oxford Dictionary which has all the list of words in it.
- **Man-in-the-Middle (MitM) Attack:** Hackers intercept communication between two parties to steal login credentials.
- **Credential Stuffing:** Attackers use previously leaked username-password pairs to try logging into multiple accounts.
- **Password Spraying:** Instead of trying multiple passwords on one account, attackers use a single common password across many accounts.

&nbsp;

## How password complexity/strength affects security
- Password complexity directly impacts security by making it harder for attackers to guess or crack passwords using brute-force, dictionary attacks, or other methods. The key factors that influence password strength are:
  
     - Length

     - Character Variety (uppercase, lowercase, numbers, symbols)

     - Randomness (avoiding patterns & common words)

     - Unpredictability (not using personal info)
 
-  Password Length vs. Security
Longer passwords exponentially increase security because each additional character increases possible combinations.

| **Password Length** | **Possible Combinations (A-Z, a-z, 0-9)** | **Time to Crack (10k guesses/sec)** |
|---------------------|-----------------------------------------|------------------------------------|
| 4 characters       | 62⁴ = ~14.7 million                     | 24 minutes                        |
| 8 characters       | 62⁸ = ~218 trillion                     | 700 days                          |
| 12 characters      | 62¹² = ~3.2×10²¹                         | 10 million years                  |

A 12-character password is vastly stronger than an 8-character one, even if both use the same character types.

- Character Variety (Complexity)
Adding different character types increases the keyspace (possible combinations), making brute-force attacks harder.


| **Password Type**         | **Example**     | **Possible Combinations (8 chars)** | **Security Level** |
|---------------------------|----------------|-------------------------------------|--------------------|
| Only lowercase            | `vintage`      | 26⁸ = ~209 billion                 |  Very Weak       |
| Lowercase + Numbers       | `hashing1`   | 36⁸ = ~2.8 trillion                |  Weak            |
| Mixed Case + Numbers      | `Devilmaycry69`   | 62⁸ = ~218 trillion                |  Medium          |
| All Chars + Symbols       | `Johnny#@69`     | ~95⁸ = ~6.6 quadrillion            |  Strong        |

Adding uppercase, numbers, and symbols makes passwords orders of magnitude harder to crack.

- Randomness & Predictability
Even complex passwords can be weak if they follow predictable patterns.

  - Strong Password: Xk7#pL$vB2% (Random, no pattern)
  - Weak Password: P@ssw0rd2024! (Predictable structure)

Dictionary attacks can crack passwords like Summer2024! quickly, even with symbols.<br>
Randomness is crucial—avoid common substitutions (@ for A, 1 for l).

&nbsp;

## Conclusion
Password strength hinges on length, complexity, and randomness. Short or predictable passwords (e.g., 123456) are cracked instantly, while long, mixed-character passwords (e.g., G$4jF#kL9@mP8!) resist attacks for billions of years. Prioritize 12+ characters, avoid patterns/personal info, and use a password manager + 2FA for maximum security. A strong password is your first defense against breaches—make it uncrackable.
