```python
GPB147_RoadMap = 
{
	"0 Full": 
		
		"""0 Hacker = [Trust in God, Seeing, Imagine(Up to Down), Doing]
		
		1 Creatures = [Machines]
		
		2 The_most_important_thing_in_the_world = [Data]
		
		3 Community_Of_Data_Hackers = [Anonymous]
		
		4 Best_way_to_income_in_world = [Selling data, Protecting data]
		
		5 Best_way_to_learn_in_world = [Basics in books, Practical in doing, Real in communication] 
		
		6 Basics_in_my_way = [English, Programming, System control, Computer, Network, Growth]
		
		7 Niche_in_my_way = [Reverse engineering, Malwares, Firmware/BIOS/UEFI and Rootkit hardware malware]
		
		8 Hackers_Language = [Russion, English]
		
		9 Computer_Programming Language = [..., Assembly(Everything of Computer, C&C++(Have Assembly Defines), Python(Have C&C++ Defines), ...]
		
		10 Computer_Control = [Terminal(PowerShell,Bash,...)]
		
		11 Computer_System = [Kernel, Windows, Mac]
		
		12 Computer = [Hardwares]
		
		13 Computer_Network = [Internet]
		
		14 Computer_Reverse_Engineering= [Defence]
		
		15 Computer_Malwares = [Attack(Rootkit, Firmware/BIOS/UEFI)]
		
		16 Growing = [GitHub, Reddit, StackOverFlow, Correboot, Freelancing, Jobs, CTF, Bug Bounties, Open Sources, Certifications, Linkedin, Conferences, Classes]
		
		17 Efficiency = [Learning, Growing, Permanent remote employment, Permanent remote employment better, Education exemption, Penetration and selling/destroing, Immigration by buying solidiering/special exemption, making my business(Hunter)]"""


	"1 Knowing" = 
	"""{
		0 Foundation:

			0 English
		
			1 Python:

				0 Books = [Automate the Boring Stuff with Python (2nd Edition)]

				1 Must to learn = [Write scripts without fear, Automate analysis, Read others’ Python]

				2 Don't learn = [Advanced Python internals, Data science, Web frameworks]

			2 Linux + Terminal: 

				0 Books = [Linux Command Line and Shell Scripting Bible (5th Edition) + Linux Basics for Hackers]

				1 Must to learn = [Bash, POSIX just for understanding, Live in terminal, Debug, script, build, flash, analyze]

				2 Don't learn = [PowerShell, zsh tricks, fish, fancy shells, Desktop Linux theory, Server administration depth, know Linux, filesystem theory, customize or beautify, treat directories as static, Learn hundreds of commands]

				3 Commands:

					0 Leanrn it = [inspect, trace, automate, build, debug]

					1 Ignore it = [customize, decorate, replace thinking]

			3 C programming:

				0 Books = [The C Programming Language (2nd Edition)]

				1 Most to learn = [Pointers are natural, Read kernel & firmware C, Understand memory bugs]

				2 Don't learn = [Modern C++ depth, STL, Application‑level patterns]

			4 Computer Architecture & Memory:

				0 Books = [Computer Organization and Design MIPS Edition 6th]

				1 Must to learn = [Stack / heap / registers, Privilege levels, Boot trust chain]

				2 Don't learn = [Quantitative CPU optimization, HPC topics]

			5 Assembly(x86, ARM, x86_64):

				0 Books = [The Art of Assembly Language (2nd Edition)]

				1 Must to learn = [Read disassembly without fear, Translate C ↔ ASM, Understand calling conventions]

				2 Don't learn = [Writing large ASM programs, Micro‑optimizations]

			6 Networking:

				0 Books = [Computer Networking: A Top-Down Approach (8th Edition)]

				1 Must to learn = [Understand packet flow, Understand packet flow, Recognize malicious traffic, Support reverse engineering & malware analysis]

				2 Tools = [Wireshark, Wireshark]

				3 Stop at = [Application layer (light), Application layer (light), Transport layer (TCP/UDP)]

				4 Don't learn = [Wireless deep dive, SDN, Advanced congestion control, Cloud networking, Network programming depth] 
	
		1 System + Kernel:

			0 Operating System Internals(OS Internet):

				0 Books = [Windows Internals (7th Edition) + Operating Systems: Three Easy Pieces]

				1 Must to learn = [User vs kernel boundary, Drivers, Boot chain OS ↔ firmware]

				2 Don't learn = [Scheduler theory depth, Filesystem internals obsession]



			1 Reverse Engineering:

				0 Books = [Practical Reverse Engineering (latest) + Reversing: Secrets of RE (2nd Edition)]

				1 Most to learn = [Reconstruct logic from binaries, Track data flow not instructions, Handle stripped binaries]

				2 Tools = [Ghidra (primary), GDB / WinDbg (support)]

				3 Don't learn = [Crackme culture, Obfuscation contests, GUI‑heavy reversing]

			2 Malware(user/kernel/rootkits):

				0 Books = [Practical Malware Analysis (latest) + Rootkits: Subverting the Windows Kernel (2nd Edition)]

				1 Must to learn = [Persistence, Stealth, Hooks, Trust abuse]

				2 Don't learn = [Web malware, Ransomware economics, Botnets]

		2 Niche Mastery:

			0 Firmware / BIOS / UEFI:

				0 Books = [The Firmware Handbook (Gary Koob) + UEFI Specification (official)]

				1 Must to learn = [Know what each component does, Know where trust is assumed, Know how it breaks, Know how to abuse it]

				2 Tools = [CHIPSEC, UEFITool, TianoCore, coreboot]

				3 Topics to MASTER = [Boot phases: SEC / PEI / DXE, SPI flash, PE/COFF, UEFI protocols, Secure Boot, Firmware persistence]

				3 Don't learn = [Full motherboard design, Electrical engineering, BIOS vendor marketing docs]

		3 Growth:

			0 Career = [The Cybersecurity Career Guide (2nd Edition), Remote research roles, Crypto / indirect payment (as you planned)]

			1 Hiring = [They connect to you, You connect to they]
		
			2 Trying = {"High demand: More", "Average demand: middle", "Low demand: Low"}

			3 Trusting(Constincy) = [GitHub, Reddit, StackOverFlow, Correboot, Linkedin, Conferences, Classes, Certifications]

			4 Showing = [Writeups(Understanding) + POC(Making), Freelancing, Jobs]

			5 Testing = [Open source contributions(Doing in real world), CTF]
	
			6 Focus = [For success you just need one of every phases(GitHub(Writeups + POC + Open source contributions))]

			7 Don't do = [Certifications obsession, Social media branding, Not followers, Non‑technical networking]	

			8 Roadmap:

				0 Github:

					0 Writeups:

						0 Means = [Underestnding Concepts]

						1 Use = [README, Wiki, docs/Documentation]

					1 POC:

						0 Means = [Proof Of Concepts]

						1 Use = [Coding]

					2 Open source contributions:

						0 Means = [Doing Concepts]

						1 Focus = [Niche, quality not quantity]

						2 Steps = [Read, Build, Use, Observe friction, Small contribution, PR, Repeat]

						3 Projects:

							0 CHIPSEC = [Hardware/firmware security testing]
		
							1 EDK II(TianoCore) = [UEFI firmware]
	
							2 coreboot = [Open-source BIOS/firmware]
	
							3 UEFITool = [UEFI image analysis]
	
							4 Ghidra = [Reverse engineering plugins/scripts]

							5 Linux kernel tooling/doc = [Small bug fixes or docs]			
	}"""	

	
	"2 Funding":

		"""0 Making Tools = [GitHun writeup + POC]

		1 Ways:

			0 Good = [Reddit, Hacker News(HN), Direct cold contact, LaborX]

			1 Bad = [Upwork, Freelancer, PeoplePerHour]
		
		2 Bidding:

			0 Position = [Every job that you making tool in that area before]

			1 Texting = [No long, No explanations, No selling yourself, Honestly]

			2 Portfolio = [GitHub link]

			3 Payment = [Crypto]

			4 Price = [Do not bid like a beggar]

		3 Don't do:

			0 sell hacking

			1 wait to "finish learning"
			
			2 argue with clients

			3 mix identity with income

		4 Roadmap = [Learning, Growing, Funding, Completed roadmap, Hiring good remote job, Learning, Growing, Making own business]""" 

	"3 Learning Process":

		"""0 = {Fri: Free+Funding, Thu&Sat: Half+Funding, Sat&Mon&Wed: Sport}
		
		1 2M = [1Seeing, 1Third Eye, 4English, 7Python, 1Buying, 1Sport, 1Clean, xGrowing, 7Sleep(10-4)]
		
		2 1M = [1Seeing, 1Third Eye, 4English, 11Linux+Terminal, 1Buying, 1Sport, 1Clean, xGrowing, 7Sleep(10-4)]
		
		3 1M = [1Seeing, 1Third Eye, 4English, 11C, 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]
		
		4 1M = [1Seeing, 1Third Eye, 4English, 11Computer Architecture & Memory, 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]
		
		5 1M = [1Seeing, 1Third Eye, 4English, 11Assembly(x86, ARM, x86_64), 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]

		6 1M = [1Seeing, 1Third Eye, 4English, 11Networking, 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]

		7 1M = [1Seeing, 1Third Eye, 4English, 11Operating System Internals(OS Internet), 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]

		8 1M = [1Seeing, 1Third Eye, 4English, 11Reverse Engineering, 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]

		9 1M = [1Seeing, 1Third Eye, 4English, 11Malware(user/kernel/rootkits), 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]

		10 4M = [1Seeing, 1Third Eye, 4English, 11Firmware / BIOS / UEFI, 1Buying, 1Sport, 1Clean, xGrowing+Funding, 7Sleep(10-4)]

		11 1M = [1Seeing, 1Third Eye, 4English 1Buying, 1Sport, 1Clean, 11Growing+Funding, 7Sleep(10-4)]

		12 Fact = [You forgot everything but important thing is RELOAD the knowledge you need fast, Forgeting is the price for being deep and deeper, And in last everything is automatic(No thinking)]

		13 Roadmap = [Learn, Done, Go to next, Forget, Reload only when needed, Automated]"""

	"4 AI(ML) Helper":

		"""0 Roadmap:

			0 Ask = [Giving data]

			1 Customized = [Receive result] 

			2 Learn = [More data] 

			3 Confusing = [Error]

			4 Ask = [Giving data]

			5 Customized = [Receive result]

			6 Learn = [More data]

			7 Completed = [Completed healthy data] 

			8 Go to next step = [Next subject]"""

	"5 Security":

		"""0 Payment Methods = [Foreign intermediary, Crypto(Web3), Platform that pay "indirectly"]
		
		1 In first start in web3 and for later apply for real remot job and after that passing technical evaluation and after that tell to company your position you are and crypto is the cleanest payment method for you
		
		2 Technical Evaluation = [See your growing, Deep discussion, Some tasks you must do]
	
		3 in technical evaluation just be your self and know in cyberseurity guys in world has like you in speaking English or don't like video chats or anything

		4 Earning Money = [Money transfered to your wallet from company, Convert to IRR gradually and in some accounts, making normal history in your account/s by saving and buying and pay rent and money earned and more, Growing your earned money by time]

		5 In earning money if they asking what is source of funds you just say freelancing, remote technical work and paid digitally and if they want proof you just show them your invoces and email agreement and work output and this process, do NOT explain things like crypto or other things, just keep it simple and boring, explain everything they just want no more

		6 Important In Remote Jobs = [Deadline, Quality]

		7 In remote jobs no matter what time you spend in project and when you work, missing deadline is normal and not communication is unusual(Explaining)

		8 Important for me = [doing my best]"""

	"6 Requirements":

		"""0 Time = [2 Year] 

		1 Laptop

		2 Internet

		3 Focus = [Empty mind of other things]

		4 Food"""

	"7 Reward":

		"""0 House = [Highest security, Best location, Small]

		1 Freedom = [Money, Time, Travel]

		2 Supporting = [Family, People like me]

		3 Respect = [Best in one thing]

		4 Own family = [Wife like me, Making fun together]"""
}
```


<a href="https://t.me/GPB147"><img width="50px" height="50px" align="center" src="https://github.com/sineme333/learn/blob/main/icons8-telegram-logo-64.png?raw=true" /></a>
<a href="https://t.me/Sineme333"><img width="50px" height="50px" align="center" src="https://github.com/sineme333/learn/blob/main/icons8-telegram-logo-64.png?raw=true" /></a>
<a href="https://www.linkedin.com/in/Sineme333"><img width="50px" height="50px" align="center" src="https://github.com/sineme333/learn/blob/main/icons8-linkedin-logo-64.png?raw=true" /></a>


