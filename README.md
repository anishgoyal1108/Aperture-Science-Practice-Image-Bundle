# Aperture Science Practice Image Bundle
**Disclaimer: This is a stub repository for a previously-made project and does not contain any actual source code.**

![image](https://github.com/user-attachments/assets/c8621f25-e5a8-4923-8daf-5b08da48e2ac)

![image](https://github.com/user-attachments/assets/32dea682-0864-4be8-a484-0d9f36e8940a)

## Introduction
This repository contains a custom set of practice images that I created based on the *Portal* and *Half-Life* video game franchises by Valve. These images were specifically designed to help participants prepare for the [CyberPatriot National Youth Cyber Defense Competition](https://www.uscyberpatriot.org/).

CyberPatriot is a national cybersecurity competition created by the Air Force Association, aimed at fostering cybersecurity awareness and education among students. In the competition, teams are tasked with finding and fixing security vulnerabilities within virtual systems like Windows and Linux. This image bundle simulates the types of cybersecurity challenges participants face in the competition, offering a fun way to sharpen their skills.

Although I made these practice images during the 2023-2024 school year, they are still widely used by my school and the broader CyberPatriot community for training and competition preparation.

## Overview
The image bundle contains two virtual machine images, one for Ubuntu and one for Windows. Each image includes 100 vulnerabilities, with a total possible score of 250 points. As with the official CyberPatriot competition, you don't need to understand pop culture to be successful; thus, a familiarity with the Portal/Half-Life universe is not required. However, for anyone curious, this is the lore for the practice images:

- **Windows Image:** The Windows image takes place on the *Aperture Science Moon Base*, a classified research facility designed to explore the limits of space-faring science. After Wheatley's disastrous antics and the subsequent abandonment of the base, the forces of The Combine are slowly encroaching on this univers, and Cave Johnson is nowhere to be found.

- **Ubuntu Image:** The Ubuntu image is set in the heart of Aperture Science's sprawling underground complex. The Combine have taken over the Earth in this universe, making Aperture Science the last bastion. You must identify and fix the vulnerabilities left by Aperture’s collapsing infrastructure and the Combine's meddling, preventing further alien control over humanity's greatest technological achievements.

## Download Links
- [Aperture Science Ubuntu](https://drive.google.com/file/d/1_ZDn7K4Xy6pQ5YXWroqBkZoIdYfSivkT/view?usp=sharing)
- Aperture Science Windows (multi-part download)
   - [Part 1](https://drive.google.com/file/d/1mN8yucgD31tVIJgWRkfYyRvegLsFHLS2/view?usp=sharing)
   - [Part 2](https://drive.google.com/file/d/1Gp22ccrHR680o9Gdi52SvZEliBRpm0G8/view?usp=sharing)
   - [Part 3](https://drive.google.com/file/d/1mo-r28xlR7aN4TUlEJGuHAkHss8W5lt1/view?usp=sharing)

## Additional Info
> Is there a live scoreboard?
- Unfortunately, there is not a live scoreboard. I couldn't find the time to set one up on top of school rigor.

> Why is auto-login disabled for Windows and enabled for Ubuntu?
- Auto-login—as convenient as it is—is considered a vulnerability in my images, even if CyberPatriot conventions dictate auto-login as necessary for the user experience.

> What are the login credentials for both images?
- The default user password is `ratman` for both images.
- Anything resembling Doug Rattmann or ratman is the default user account.

> What is the difficulty of the images?
- In my opinion, the difficulty is between state and semifinals (basically Rounds II/III). People might feel differently depending on their experience level.

> What virtual machine platform/software was this made for?
- These images were made for VMWare Workstation Player/Pro version 17 or higher. Please make sure that you have *at least* version 17 before opening the images.
  
> How large are the VMs?
- Post-extraction, Ubuntu is ~30 GiB and Windows is ~38 GiB, respectively.
- Both disks were defragmented prior to release to ensure the an optimized user download/launch experience.  
- Since the disks are defragmented the images might take abnormally long to launch the first time, but every time after that should be relatively quick. If not, check your RAM and CPU allocation

## Answer Keys
- [Aperture Science Ubuntu](<https://drive.google.com/file/d/1FZvMhCCAt78CQvEpawQVtCBdh4umK-0f/view?usp=sharing>)
- [Aperture Science Windows](<https://drive.google.com/file/d/11yk-ylOE7zancN6HCudMC8zP1zb9hCBc/view?usp=share_link>)

## Acknowledgements
This practice image bundle was made possible by:
- [aeacus](https://github.com/elysium-suite/aeacus), an open-source vulnerability remediation scoring system.
- [sarpedon](https://github.com/elysium-suite/sarpedon), an endpoint for aeacus that allows quick deployment. I used this to track and score the images for my school in real time.
