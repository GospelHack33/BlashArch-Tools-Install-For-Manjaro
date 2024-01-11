# BlashArch-Tools-Install-For-Manjaro
Turn Your Manjaro Os Into A Hacking Box!!!

curl -Os https://blackarch.org/strap.sh

chmod +x strap.sh

sudo ./strap.sh

<h2>BlackArch Categories</h2>
webapp: A collection of tools designed for exploiting web servers and enumerating vulnerabilities in web applications.

fuzzer: A collection of tools designed for fuzzing, which is often defined as automated bug finding or "throwing" random input data at an application to invoke interesting or unwanted responses.

scanner: A collection of scanners that includes SSL scanners, SQL Injection scanners, CMS scanners, and much more.

cracker: A collection of tools designed for cracking cryptographic functions, as well as brute-forcing tools.

forensic: A collection of tools designed to find data on physical disks and embedded memory.

proxy: A collection of tools designed to act as a proxy or redirect traffic to another server on the internet.

mobile: A collection of tools designed to manipulate mobile platforms.

code-audit: A collection of tools designed to audit existing source code for vulnerabilities.

fingerprint: A collection of tools designed to exploit fingerprint biometric equipment.

<b>We can install entire categories by typing the below command into a terminal. Substitute <category> for the category name above that you want.</b>
sudo pacman -S blackarch-<category>

<b>For a complete list of BlackArch categories, run the below command.</b>
sudo pacman -Sg | grep blackarch

<b>Alternately, we can view the official BlackArch guide for more details. We can also install all 2,200+ available tools with a single command. This would take a considerable amount of time. If you're feeling patient, use the below command to install everything BlackArch has to offer.</b>

sudo pacman -S blackarch



