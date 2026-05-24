# Algo_Riot

## Project Overview

`Algo_Riot` is a semester project for the NSCS module on Algorithms and Static Data Structures. It is a C-based security utility suite that combines user management, audit/security analysis, encryption, log management, and math/security helper tools.

## Main Features

- **User Management**
  - Display users
  - Add/delete users
  - Search users
  - Change passwords
  - Login verification
  - Block/unblock accounts
  - Role assignment (admin/user)
  - Save/load user database
  - User statistics and admin listing

- **Audit & Security Analysis**
  - Password strength testing and scoring
  - Random password generation
  - Hex key generation and validation
  - Text statistics analysis
  - Email and login format validation
  - Security report generation
  - Global security level assessment

- **Encryption & Cryptography**
  - Caesar cipher encrypt/decrypt
  - Substitution cipher encrypt/decrypt
  - XOR encryption/decryption
  - Message formatting tools (uppercase, lowercase, remove spaces, reverse)
  - Frequency analysis and coincidence index
  - Message comparison and character counting

- **Log Management**
  - Display and add logs
  - Search logs by user/date
  - Log statistics and error analysis
  - Export/import CSV logs
  - Sort logs by date/user
  - Archive logs and detect suspicious activity

- **Math & Security Tools**
  - Number analysis: primes, gcd/lcm, factorial, perfect/Armstrong checks
  - Matrix operations: add, multiply, transpose
  - Array statistics: sum, average, min/max, sorting
  - Random number generation and security-related utilities

## Repository Structure

- `mian.c` - Main program with menu-driven interface
- `library/` - Header files for each module
- `src/` - Source implementations for each module
- `library/output/` - Example build or output folder

## Build Instructions

From the `Algo_Riot-1` folder, compile with `gcc`:

```sh
cd /home/k/Desktop/re/securec_v2/Algo_Riot-1
gcc mian.c src/*.c -o Algo_Riot -lm
```

Then run:

```sh
./Algo_Riot
```

## Notes

- The program uses ANSI color codes for terminal output.
- Default maximum users and logs are set in `mian.c`.
- Admin-level menus are protected and only available to users with role `admin`.

## Target Audience

This project is designed as an educational tool for first-semester students learning C, algorithms, static data structures, and basic security concepts in the NSCS module.

## Contact

For improvements or fixes, review the source files under `src/` and the module headers in `library/`.