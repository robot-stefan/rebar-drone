## Robotic Drone for Rebar Automation

From 2018 to 2022 I worked on a construction technology startup which pivoted to the rebar / reinforced concrete space. Initially we had looked at onsite logistics for construction sites using drones to move items less than crane picks around sites. A large kit drone was used to test concepts and to create some media for networking with contruction companies. After several site visits and combing through months of OxBlue cameras[^oxblue] from multiple jobs sites it was found that rebar work seemed to be consistently on the critical path. This pivot occurred during The Farm startup accelerator hosted by Comcast[^comcast] Central Division and Boomtown[^boomtown]. This led to gathering a support letter, conducting basic perception & flight testing, and securing enough market study info to submit for a National Science Foundation Phase 1 SBIR[^SBIR] grant. The NSF grant was one of many we sumitted during the accelerator for the various markets we studied and was the only one which was awarded. Finding funding for early stage hardware startups (sometimes called deeptech or hardtech in the startup world) can be very difficult most of the time and particularly so in the southeast US. 

| P3 Rebar Drone | Logistics Drone Concept Test|
| :---: | :---: |
|![image_of_rebar_drone_indoors](images/rebar-drone-indoor-flight-test.jpg)|![image_of_logistics_drone](images/logistics-drone-demo.jpg)|

Once the grant was awarded and we were able to start working under its funding, we worked to progress rapidly through multiple iterations on the system both hardware and business case front. The large drone above sitting indoors represented a 3rd iteration of the system and is close to the final state of the platform. This iteration was started after a demo event in November of 2019 where we were invited to present as part of a Verizon disaster response exercise[^ocr] demonstrating how next generation wireless networks will enable rebuilding infrastructure with tools such as robotics and intelligent machines after a wildfire. This event provided us with a sand box environment for the better part of a week. Outside of the demos for the event we were able to conduct systems tests till we ran out of daylight each day gaining valuable insights on deployment, field ops, and needed refinements to many of the subsystems. Many of these elements were only uncoverable by deploying the system and this event greatly sped up development. 

| Exercise Demo | Test Near Sunset | P2 v P3|
| :---: | :---: | :---: |
| ![image_of_demo](/images/rebar-drone-disaster-fire.jpg) | ![image_of_test_near_sunset](/images/rebar-drone-disaster-test.jpg) | ![image_of_P3vsP2](/images/rebar-drone-P2vP3.jpg) |

The next development cycle started immediately in December and the larger drone was first assembled in mid-January of 2020 for display at World of Concrete[^woc]. Following the January trade show, development efforts in 2020 focused on iterations to the tooling system, sensor integration testing, and flight control. For comparison, P3 was a big jump in size compared to P2. P2 could fit under P3. For the hardware my focus was on mechanical design, system architecture, harnesses, and sensor selection & placement. I was also focusing on business development efforts such as customer interviews, performance studies for benchmarking, discovery of ways to service customers such as development of a sales/support channel.  Efforts were split across getting progress on as many fronts as feasible be it hardware development or business development.


[Business Development](BusinessDevelopment.md)

[Hardware Development](HardwareDevelopment.md)


[^oxblue]: [OxBlue](https://www.oxblue.com/) A brand of timelapse cameras for construction sites. A few construction companies were annoyed enough that they gave us links to their camera feeds for sites and told us to knock ourselves out. 
[^woc]: [World of Concrete](https://www.worldofconcrete.com) The second largest trade show annually held in Las Vegas and the largest tradeshow dedicated to construction and a leading building material used by humanity for the past 2,000+ years. 
[^comcast]: [Comcast](https://corporate.comcast.com/)
[^boomtown]: [Boomtown Accelerators](https://btinnovation.com/)
[^ocr]: This event was called Operation Convergent Response and was hosted by Verizon, Nokia, and the [Guardian Centers](https://guardiancenters.com/) for serveral years and has since stopped. 
[^SBIR]: Small Business Innovation Research all US federal government agencies offer one as required by congress. The NSF program is one of the more broad ones in that the NSF focuses technologies which can provide society scale impact and improve the national economy. The NSF is also one of the most competitive grants to acquire. [More can be found out here.](https://seedfund.nsf.gov/)
