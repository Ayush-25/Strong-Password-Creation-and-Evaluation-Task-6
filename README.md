# Strong-Password-Creation-and-Evaluation-Task-6
Understand what makes a password strong and evaluate its strength using PasswordMonster.com. This task develops awareness of password security, complexity, and resistance to attacks.

## Tools Used
- **PasswordMonster.com (Free Browser-Based Strength Checker)**   
- Target: Local PC Browser  

---

## Methodology and Steps

### Step 1: Create Multiple Passwords  
Constructed four test passwords with varying complexity:  
- `Password1135799` (Weak)  
- `Pa$$w0rd!2025@50%` (Medium)  
- `GreenApple$87!u` (Strong)  
- `M!cr0$0ft_CyB3rS3cur!ty@2025` (Very Strong)  

*Screenshot:*  
<img width="452" height="213" alt="image" src="https://github.com/user-attachments/assets/db06405d-e676-4810-8cd3-e94e8f8dc9d8" />

---

### Step 2: Open PasswordMonster  
Opened the PasswordMonster website to input and test passwords.  

*Screenshot:*  
<img width="1904" height="797" alt="Screenshot 2025-09-30 100443" src="https://github.com/user-attachments/assets/3354ef9e-97c5-4a76-9bd1-dc3104c4ad9b" />

---

### Step 3: Test Each Password  
Entered passwords one by one and captured strength feedback, time-to-crack estimates, and vulnerabilities pointed out by the tool.

*Screenshots:*  
- `Password1135799` test → weak feedback
<img width="1359" height="706" alt="Screenshot 2025-09-30 104141" src="https://github.com/user-attachments/assets/e394341f-04a5-4c63-81cc-7df317940508" />

*Screenshot:* 
- `Pa$$w0rd!2025@50%` test → medium feedback
<img width="1404" height="764" alt="Screenshot 2025-09-30 104403" src="https://github.com/user-attachments/assets/9d4af12b-c8a8-4df9-a76d-6926b3456a55" />

*Screenshot:* 
- `GreenApple$87!u` test → strong feedback
<img width="1386" height="726" alt="Screenshot 2025-09-30 104741" src="https://github.com/user-attachments/assets/f37b5dab-4655-436d-b935-1c71b569aeed" />

*Screenshot:* 
- `M!cr0$0ft_CyB3rS3cur!ty@2025` test → very strong feedback
<img width="1366" height="727" alt="Screenshot 2025-09-30 104825" src="https://github.com/user-attachments/assets/0b0eb031-559f-42c4-af1b-d00f765c3d1a" />
 
---

### Step 4: Compare Results

| Password                   | Strength Level | Feedback / Weaknesses Noted |
|-----------------------------|----------------|------------------------------|
| `Password1135799`           | Weak           | Numeric sequence, predictable, lacks symbols |
| `Pa$$w0rd!2025@50%`         | Medium         | Mixed characters, but common pattern |
| `GreenApple$87!u`           | Strong         | Good mix, passphrase style, unique words |
| `M!cr0$0ft_CyB3rS3cur!ty@2025` | Very Strong  | Long, complex, high entropy |

---

### Step 5: Research Password Attacks  
- **Brute Force Attack:** Brute Force Attack:
A brute force attack systematically tries every possible combination of characters until it finds the correct password. The time required grows exponentially with password length and character set (lowercase only vs. lowercase+uppercase+digits+symbols). Attackers often use GPUs and distributed systems to speed up the process, testing billions of guesses per second. Long, complex passwords greatly increase resistance.
Example: A 6-character lowercase password like monkey can be cracked in seconds, but a 16-character mixed password like M!cr0$0ft_CyB3rS3cur!ty@2025 would take millions of years.

- **Dictionary Attack:** A dictionary attack uses a predefined list of common words, leaked passwords, or variations to guess passwords instead of trying every combination. Because many users pick simple or common passwords, this attack is often very effective and faster than brute force. Attackers also use rules to modify dictionary entries (e.g., replacing a with @).
Example: If someone’s password is Password123, it will likely appear in a leaked password list and be cracked almost instantly by a dictionary attack.

- **Rainbow Table Attack:** A rainbow table attack relies on precomputed hash databases that map plaintext passwords to their hash values. If a stolen password hash matches one in the table, the attacker instantly learns the password without needing to guess. Rainbow tables are only effective against unsalted or weakly hashed passwords.
Example: If a website stores 123456 hashed with unsalted MD5, an attacker with an MD5 rainbow table can look up the hash e10adc3949ba59abbe56e057f20f883e and immediately recover the original password 123456.
---
### Step 6: Best Practices & Lessons Learned  
- Use **14 or more characters**, longer when possible.  
- Combine **uppercase, lowercase, numbers, symbols**.  
- Avoid using common substitutions (e.g. “E → 3”) alone — attackers know these tricks.  
- Prefer **long passphrases** over short complex strings.  
- Never reuse passwords across multiple sites.  
- Use a **password manager** to generate and store high-entropy passwords.

---

## Outcome  
- Gained hands-on experience evaluating password strength using PasswordMonster.  
- Learned how complexity, length, and unpredictability contribute to resistance against brute force, dictionary, and rainbow-table attacks.  
- Collected concrete tips to build strong, secure passwords in real life.

---

## Contact  
**Ayush Singh**  
Email: ayushsinghfeb2502@gmail.com  
