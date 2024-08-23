# Goldman Sachs Software Engineering Job Simulation

## Overview

This repository documents a job simulation completed as a Governance Analyst at Goldman Sachs. The project focused on assessing IT security and recommending improvements to enhance password protection.

## Project Details

### Password Security Analysis

- **Objective:** Assess the company's password hashing mechanism to identify vulnerabilities.
- **Method:** Utilized Hashcat to crack hashed passwords and discovered the use of the outdated MD5 hashing algorithm.
- **Findings:** Identified several weaknesses in the current password protection scheme.

### Recommendations

Based on the analysis, the following recommendations were proposed to improve password security:

1. **Upgrade Hashing Algorithm:**
   - Move from MD5 to a more secure algorithm such as bcrypt, scrypt, or PBKDF2.
   
2. **Implement Salting:**
   - Introduce unique salts for each password before hashing to prevent the use of precomputed tables.

3. **Increase Minimum Password Length:**
   - Raise the minimum length requirement to at least 12 characters to enhance security.

4. **Enforce Password Complexity:**
   - Require passwords to include a mix of uppercase letters, lowercase letters, numbers, and special characters.

5. **Educate Users:**
   - Promote best practices for creating strong passwords, such as using passphrases and password managers.

### Memo

A comprehensive memo summarizing the findings and recommendations was prepared for presentation to the supervisor. The memo includes detailed suggestions for improving the organization's password protection measures.

## Files

- **`analysis_results.txt`**: Contains the results of the password analysis.
- **`hashed_passwords.txt`**: Contains the hashed passwords.
- **`memo_to_supervisor.pdf`**: The final memo outlining the proposed uplifts for password security.
- **`hashcat_script/`**: Directory with Hashcat scripts and configurations used during the analysis.


 
