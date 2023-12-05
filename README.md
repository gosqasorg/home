# Global Open Source Quality Assurance System (GOSQAS)

This is the starting place for the GOSQAS (GAHS-kwahs) system. GOSQAS and related marks and logos are trademarks of the Global Assurance Quality Assurance System, a US partnership registering as a corporation in California. All of our code is open source but we reserve all rights on our trademarks (see below).

The Global Open Source Quality Assurance System (GOSQAS) was formed to promote trust in open source medical devices and supplies. GOSQAS believes that increasing transparency around the quality and safety of these devices is necessary for global acceptance. To achieve this, GOSQAS has developed a ''Trust Through Transparency'' (TTT) approach to ensure the safety and efficacy of medical devices made from open source designs. This approach includes a GOSQAS seal with QR codes for device information, Unique Device Identifiers, and a Provenance system to track the complete manufacture and transport history of the device.

The first tool produced by GOSQAS is called Global Distributed Tracking (GDT), which is the system discussed here. GDT is completely free-of-charge, as well as free software.

# Functional Demo

On June 8th, @devhawk (Harry Pierson) wrote a [quick-and-dirty demo](https://github.com/gosqasorg/asset-provenance-tracking) that he quickly developed into fully functional [minimum viable product (MVP)](https://github.com/gosqasorg/asset-provenance-tracking). We made a brief [video screencast](https://www.youtube.com/watch?v=6FK8fXuefZQ) of this demo.


# Features
The GDT system allows anyone with a device to trace the provenance and add to it using a simple website. The Seal provides a quick visual impression of the top certifications, and the Key is used to decode the entire provenance. GOSQAS is compatible with existing regulatory bodies, not a competitor, and supports the labeling and tracking of devices and support for decentralized additive manufacturing. GOSQAS will defend marks and logos legally in order to avoid confusion but will be fiercely open in its technology. The GOSQAS system will be implemented in phases, starting with a Maker’s Mark, self-asserted quality, Global Trade Item Number, cryptographically strong provenance, and community provenance checking. This will lead to the GOSQAS seal becoming a visually recognized seal of quality worldwide.

You may wish to watch this video of a talk we recently delivered at FOSDEM'23 introducing the concept:
[![Screen Shot 2023-02-09 at 12 35 15 PM](https://user-images.githubusercontent.com/5296671/217906194-c8b240d1-038c-4da3-a633-cbf5306b1877.png)](https://ftp.osuosl.org/pub/fosdem/2023/AW1.120/publiccode_dpg_qa_emergency_supplies.webm)

# Real World Use Cases

Here are some real-world use cases that may show the versatility of the GDT provenance tracking system:
* Glia [Stethoscope](https://gosqas.org/provenance/JpTWM818HuBbvvsZFQmYQA)
* [Oatmeal Raisin Cookies](https://gosqas.org/provenance/5gckf76pbwP77ri4qaSdck)
* Live Demo: [Nasogastric Tubes](https://gosqas.org/provenance/AkFBdE7GNHHQQVnsdPjegR) 
* Oxygen Concentrator [Maintenance](https://gosqas.org/provenance/65UFxsaUtfM3WbmHr4o7Ch)
* Corsi Box [Construction](https://gosqas.org/provenance/VfPLp8T6DhtzKd2nz93fFJ)

As an exercise, try to think how you would use GDT for your own work!

# Drafts of Technical Papers

Although very much a work in progress, we have written two long-form papers about GOSQAS and the Asset Provenance Tracking system. We invite you to read and even comment on these papers, but understand that they are rough drafts at the moment.
1. [How the Global Open Source Quality Assurance System (GOSQAS) will Promote Global Trust in Open Source for Medical Devices and Supplies](https://docs.google.com/document/d/1CkJ3Tz7I6DO1TV4CgKxCUxyvJEqqtBEu/edit?usp=sharing&ouid=118089335094003856513&rtpof=true&sd=true) is our basic introductory document.
1. [Provenance Tracking For Low-to-Medium Value Distributed Manufacture](https://docs.google.com/document/d/1zEo3x8z_9rtaa8uSj5YuizLrt8Tz5z_DJQiyNo9J6K8/edit?usp=sharing)


# Who We Help

The GOSQAS asset provenance tracking system is independent and cooperative with regulatory bodies such as the FDA. For example, GOSQAS may be used by a distributor making regulated devices to implement some of it regulatory burden with respect to market surveillance and recall. 
Although it can be used by a large manufacturer to internally track assets, its main goal is to empower rapid, distributed manufacture, 
perhaps in response to natural or man-made disasters. Such manufacturers may not have control of their ingoing or outgoing supply chain.
An open, transparent system that makes it easy for them to document their work makes it more likely to have an impact.

* Manufacturers get an easy opt-in way to make their devices more trustworthy by getting identifying keys and easily documenting manufacture and test.
* Distributors have an easy way to maintain chain-of-custody and maintenance to increase trust for buyers.
* Buyers get an easy way to check chain-of-custody to avoid counterfeits and understand quality transparently.



# Roadmap for Software and Features

We now have a minimal but functional system. However, we could still use competent volunteer help to add features:
* Better tag recognition
* Support for hierarchical container tagging

## Cultural Development Roadmap

Concurrent to the software roadmap, we also need "social developments" which are not embodied in software. We need to develop a culture of:
* Using standardized quality assurance tests and documenting them.
* Sharing knowledge about how to evaluate a provenance.
* Developing a culture of authenticating quality assurance tester identity.
* Developing best practices that make fraud impractically difficult.


# A Note on Our Trademarks

Although all of our code is open-source, you may not use our trademarks without written permission.
Our trademarks include:
1. The word GOSQAS
2. The term "Global Open Source Quality Assurance System"
3. The "purple hands" logo
4. The word-ard GOSQAS with the "purple hands" symbol in the letter O.
5. The phrase "Global Distributed Tracking"

# Licenses

Unless otherwise labeled, everything in the repo is licensed under the [Public Invention License Guidelines](https://github.com/PubInv/PubInv-License-Guidelines), which specifies different licenses for different kinds of matter:

Material | License
------------ | -------------
Software | [GNU Affero GPL v3](https://www.gnu.org/licenses/agpl-3.0.en.html)
Web-delivered Software | [GNU Affero GPL v3](https://www.gnu.org/licenses/agpl-3.0.en.html)
Hardware | [CERN Open Hardware Licence Version 2 - Strongly Reciprocal](https://ohwr.org/cern_ohl_s_v2.txt)
Documentation | [CC0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain) 
Scientific Articles | [Creative Commons Attribution-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nd/4.0/)
Freehand Graphic Art | [Creative Commons Attribution-ShareAlike 4.0 International License (CC-BY-SA)](https://creativecommons.org/licenses/by-sa/4.0/)
Diagramatic Graphic Art | [Creative Commons Attribution-ShareAlike 4.0 International License (CC-BY-SA)](https://creativecommons.org/licenses/by-sa/4.0/)
Regulated Medical Devices | [CERN Open Hardware Licence Version 2 - Strongly Reciprocal](https://ohwr.org/cern_ohl_s_v2.txt) or [Public Invention Sunlight Regulatory Agreement (WIP)](https://github.com/PubInv/RegulatorySunlight)

# Our Partners

![PartnerLogos_2 0 (1)](https://github.com/gosqasorg/home/assets/64275888/aa0e2b2b-e7b0-4ded-b239-1f93683677a5)

# Contributing

This is a (mostly) volunteer effort and we need your help. We are organizing volunteers at the [main working repo](https://github.com/gosqasorg/asset-provenance-tracking), please go there and see the Contributing
section of the README, where you will see how to email us directly.

