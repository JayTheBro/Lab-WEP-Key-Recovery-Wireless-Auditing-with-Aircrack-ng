# Lab-WEP-Key-Recovery-Wireless-Auditing-with-Aircrack-ng

Objective: Demonstrate the cryptographic weaknesses of Wired Equivalent Privacy (WEP) by recovering an encryption key from a sample packet capture file using the Aircrack-ng CLI suite.
Tools Used: Aircrack-ng (Windows CLI), Windows PowerShell

Methodology:
Environment Setup: Downloaded the Aircrack-ng Windows binaries and configured temporary Windows Defender folder exclusions to allow execution of the security auditing .exe files in an isolated lab environment.
Packet Analysis & Key Recovery: Executed Aircrack-ng via PowerShell against an official sample .cap file. Using statistical cryptanalysis and key testing, the tool recovered the target WEP key after evaluating 1,941 potential keys.
Cleanup: Removed temporary antivirus exclusions upon completing the lab.

Key Takeaways:
Gained practical familiarity with command-line wireless auditing tools.
Reinforced why WEP is obsolete: flaws in RC4 key scheduling and short Initialization Vectors (IVs) allow attackers to recover keys quickly once sufficient network traffic is captured.
