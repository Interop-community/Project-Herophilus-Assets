[comment]: <> (![iDaaS Word Art]&#40;images/iDAAS-Web-WordCloud.png&#41;)

# Background
Open Source or the "community" development model has been used in software development for almost two decades. Over the 
last decade all significant software innovation in the past 10 years has been from open-source communities. Here is a
<a href="https://www.redhat.com/rhdc/managed-files/rh-enterprise-open-source-report-f27565-202101-en.pdf" target="_blank">report</a>
that showcases all the various ways open source and it's culture is transforming the way not only software is delivery but 
changing the way new innovation is being delivered. Healthcare for many decades has also relied upon community development 
in areas such as treatment protocols, safety standards, and industry standards based data formats. Now, as we head into
a new era driven by comsumption and secure managed services it is a perfect time in healthcare for open source and 
healthcare.

Welcome to Project Herophilus, this GitHub based organization is intended to be an open source upstream healthcare 
community with a specific focus around build data driven assets. In order to help healthcare it was critical that we 
define [specific design principles](docs/Design/DesignPrinciples.md) to ensure a very [scalable, extensible and reusable architecture](docs/Design/Architecture.md) with a focus on enabling 
specific [capabilities](docs/Design/Capabilities.md). The intent of this organization is two fold: help drive 
data driven open source capabilities into healthcare while demonstrating how healthcare can leverage open source to 
solve industry problems!!! Why the name? Herophilus or spelled Herophilos, Herophilus was a Greek physician who is often 
credited with being the founder of Anatomy. Assets currently available provide tools for configuration, testing, 
data integration, synthetic data, and more - all developed and available to any organization. Project Herophilus has 
made these assets available to anyone using fully open source software and all under Apache 2 licensing.

Project Herophilus intent is to help with various areas related to data challenges consistently seen across all areas of 
healthcare for decades. We created a [fictious organization](docs/General/FictitiousOrg.md) for consistency. 
The overall project is intended to deal with [integration standards support](docs/Design/IntegrationStandardsSupported.md)
and non industry standard data challenges. At Project Herophilus we [leverage industry leading open source technologies](docs/Technical/Technologies.md) 

- Intelligent DaaS (Data as a Service): Simplify and enable easier and more consistent access to data. It is intended to be 
a comprehensive set of <b> design patterns / reference architectures / accelerators </b> to help anyone and supports hundreds
of connectors from legacy to modern to industry standards to various public clouds. It includes the ability to connect, 
route/distribute, build business process/decision management based apps and provides comprehensive audit capabilities.  
- Event Builder: Comprehensive parsing and data building library for a comprehensive set of healthcare data standards.
- Synthetic Data: The ability to leverage billions of data attributes in any number of ways to maximize business needs
and benefits.
The platform is constructed in a very modern cloud native manner ensuring that any component is designed and built for 
a specific purpose with scale and extensibility. The sole purpose of ALL the capabilities we have built for healthcare 
is to enable <b> Data as an Asset</b>. The major focus of our efforts is to reduce, and hopefully remove, the data barriers
while reducing risk and moving data integration towards <b>Data Innovation</b> and enable it to move from a specific task based 
enabler to a mainstream application development enablement.

# How to Get Started
In the background section we tried to giv and quick and simple definition for what we are doing. However, as you can imagine
with all the capabilities enabled and supported are massive. After seeing all the types of
<a href="https://camel.apache.org/components/3.13.x/index.html" target="_blank">connectivity natively supported</a>.
Then, you can check out our [technical guides](docs/Technical/intro.md) to see how to build out various development 
environments. Then, I would look at the [various repositories](docs/Design/PlatformComponents.md) and the specific 
capabilities they enable. The final step we would recommend is looking through the [implementation guides](docs/ImplementationGuides/intro.md)

# Where Are We Headed
We have numerous [Technical Advisors](docs/General/TechnicalAdvisors.md) that help ensure we are addressing healthcare 
industry needs. Beyond our technical advisors we have received key sponsorship from Red Hat. Red Hat who is a leader in 
enterprise open source and offers support, security, services and training. Red Hat is keeping its enterprise open source 
leading approach and operates a subset of these assets “downstream.” While the “accelerators” are provided as is, Red 
Hat customers can get secure and supported software the “accelerators” run atop for their production and other business 
needs. For more information please feel to go to https://github.com/RedHat-Healthcare/. Several efforts from Project Herophilus 
are forked here and other branded efforts are named the same. Some of these cannot be forked as they leverage completely 
different libraries and go through a seperate build and testing process; however, the capabilities they deliver are the same.

Please feel free to go to our discussion  and/or issues areas in any of the specific repositories. We consider all 
feedback as we are looking to improve our design pattern/reference architecture. Any communication to these areas 
or the project owners influences our [Technical Roadmap](docs/Roadmap/index.md).

## General Industry Content

| Content|
| -------------|
| <a href="https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/IndustryPublishedContent/CMS/CMS-Interoperability%20and%20Data%20Access%20Final%20Rule.pdf" target="_blank">CMS Interoperability Final Rule</a>|
| <a href="https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/IndustryPublishedContent/ONC/ONC_Cures_Act_Final_Rule_03092020.pdf" target="_blank">21st Centrury Cures Act</a>|
| <a href="https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/IndustryPublishedContent/FHIR/USCDI-Version-2-July-2021-Final.pdf" target="_blank">US CDI v2 Standard</a>|

<br/>
<i>Happy coding!!!!</i>
