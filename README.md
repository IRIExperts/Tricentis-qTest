# Enterprise qTest Migration Strategy

Enterprise Testing Strategy involves adoption of tool (s) that can help drive the overall Testing processes in a collaborative & effective manner.

There are many Test Management Platforms in the market today that allows Testing Teams to manage their needs around:
1.	Requirements
2.	TestCases (Manual)
    *	Development
    * Execution
4.	Reporting
5.	Defects
6.	Integrations

Overtime, with the adoption / usage of the Test Management Platform within the teams / organization, the volume of artifacts grows significantly.

The investments done in terms of efforts and money are not easy to let go even if the Organization is in the phase of onboarding a new Platform aligned with thought leadership / innovation initiative.

## Business Need (Saving The Existing Investment):
For Enterprises that are transitioning from legacy Test Management Platforms to qTest, there is always a question around “Saving The Existing Investment” by exploring the possibilities of migrating the artifacts (based on feasibility) from existing tool (s) to qTest.

From qTest perspective, there are APIs available that allows to retrieve and create all supported types of artifacts and can be leveraged to plan & execute Migration projects.

## Approach
Migration approach is similar to “Extract, Transform & Load” approach wherein the artifacts from existing tools are:
*	Retrieved / extracted through available APIs or in a format that can be parsed e.g., JSON, XML, Excel, .TXT, .DB etc.,
*	Objects and their properties (Standard and Custom) are mapped from Source to Target and Parser / Custom Utility is written to Transform the Source Mapping to technically acceptable Target Mapping
*	Target tool APIs are leveraged to Load the mapped data into the tool repository

Note: Migration, ideally, is done to Load artifacts only once and post migration, the Target Tool / Platform (in our case, qTest) is used to develop any new artifacts.

![migration approach](https://github.com/IRIExperts/Tricentis-qTest/blob/main/1.png "migration approach")
 

The migration approach generally involves below phases based on the complexity and overall scope of migration project:
*	Analysis & Feasibility Check
  - This phase involves analysing the Source Tool artifacts over a call and visualize the object mappings
  - This phase can be further extended by requesting an Export of the artifacts from Source Tool or by checking the APIs of Source Tool to ensure that the required information is accessible to perform the actual migration activity
*	Scope & Effort Finalization
  - Based on the initial analysis, the overall scope and effort for performing the migration project is finalized and agreed upon
*	Continuous Development, Testing, Deployment & Delivery
  - The development of the migration solution / utility is done iteratively by continuously developing the overall migration capability, testing and deploying in customer environment for ensuring that the required migration is achieved
  - The iterative approach needs involvement from customer team as well to ensure that the final agreed stage of the migration is achieved
*	Documentation & Sign Off
  - Post the final deployment and testing of the migration solution / utility, a detailed documentation is prepared and walkthrough of the overall migration activity is shared with the customer





## IRI Expertise:
We at, IRI, are currently developing solutions / utilities around migrations from different platforms to qTest and are following a methodical approach to:
* develop a Migration Platform with the flexibility to plug any Source Tool and perform migration by developing Source specific parser / transformer embedded into the Migration Platform (Future State)
* leverage GenAI capabilities to identify the % of migration achieved and major gaps from Source to Target (Future State)

Below is IRI’s view from thought leadership perspective around migrations:

### Current Desired State:
* Develop baseline migration solutions for commonly observed existing Test Management platforms e.g., QC / ALM
* Leverage the baseline implementation to develop uniform migration platform with an architecture that can be extended through Plug & Play approach with configurable object mapping possibilities
	

### Future Roadmap:
* Plug & Play Platform
* GenAI Capabilities

 ![migration approach](https://github.com/IRIExperts/Tricentis-qTest/blob/main/2.png "migration approach")

We are open towards getting engaged with any Enterprise Migration opportunities and leverage our expertise to assist organizations to transition towards qTest in a seamless and effective manner.
