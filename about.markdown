---
layout: default
title: The Research
permalink: /about/
---

The driving force behind the eGuardian angel project is a desire to remove the increasing burden on the healthcare system. The eGuardian angel model seeks to shift caregiving from being the sole role of clinicians to being a patient focused model, particularly in the realm of chronic disease treatment and management, as well as rehabilitation. The aim of the eGuardian angel project is to harness the role social connection plays in the physical and mental health of individuals, so as to improve the quality of healthcare received by individuals, whilst also effectively managing the increasing demands that current clinicians and healthcare services face.

<style>
    #video_container {   position: relative;
							padding-bottom: 56.25%;
    						padding-top: 35px;
    						height: 0;
    						overflow: hidden }
</style>

<style>
    #video { position: absolute;
    			top:0;
    			left: 0;
    			width: 100%;
    			height: 100%;}
</style>

<div id="video_container">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/Y28n9I9V-fw" id="video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
	</iframe>
</div>

# Social Contagion

Social contagion theory, as introduced by Nicholas Christakis and James Fowler in their 2011 paper, "Social contagion theory: examining dynamic social networks and human behaviour", describes a situation where the attitudes of one person can influence others at a range of up to three degrees of separation. The two focuses of the eGuardian App are more specifically emotional contagion and motivational contagion, as the aim of the project is to increase both the positivity of individuals in respect to their treatment and recovery, as well as the motivation individuals have to follow medical recommendations including lifestyle choices and medication regimens.

# Anonymity

Participation in the eGuardian Angel Project as either a 'Child' or an 'Angel' is anonymous, meaning other people within the
program will not be aware of your identity, and you will not be aware of theirs. This is because studies have found that
individuals, particularly in an online environment, are more likely to open up about their experiences when they feel they have anonymity. For individuals to get the largest possible benefit from the application, it is essential that they feel they can be transparent with others and communicate freely, without fear of judgement. To counteract the potential negative effects of anonymity in the application, the application allows any individual to report their 'Angel' or 'Child' if they feel they are adversely affecting them or are taking advantage of the anonymity feature to give negative feedback without fear of consequences.

# Network Topologies

During the research and development phase of the eGuardian Angel Prototype, multiple network topologies were modelled using agent-based computer simulations. These simulations were conducted in order to determine what the most effective structure would be in practice. Whilst all three network topologies that were modelled showed overall increases in positivity and motivation indicators, the distribution of the benefits were very varied in the three simulations. As the aim of the eGuardian Angel system is to see the largest possible benefit for the largest number of people, this distribution of benefit was the largest factor taken into consideration when determining which topology to use in practice.

## Ring

The ring topology connects individuals such that every individual in the network is the angel of one person, and the child of another. The simulations conducted found that the ring topology network was the most effective way to make sure everyone within the network got the largest overall benefit in terms of their positivity and motivation. The flow-on effect that is seen in this model is evidence of the powerful force of social contagion. Due to the ring topology having the largest benefit for the largest number of users, it was selected to be used in the prototype for the eGuardian Angel App.

## Random

The random topology, as the name suggests, connects individuals in the network in an unorganised way. Whilst the model does ensure that every individual in the network is connected to at least one other, there is no guarantee that each individual both receives advice and gives it. This limits the capacity for the benefits of social contagion to be felt. Through modelling the random network, it was seen that some individuals saw excellent results, due to the high number of connections they had, whilst others saw an overall decrease in motivation and positivity due to the uneven delivery of care. For this reason, the random topology was not used in practice, as we desired to see the greatest impact, for the greatest number of patients.

## Point-to-Point

The point-to-point topology, which is also commonly referred to as the pair-buddy network, connects individuals in isolated, two-way relationships. With this topology, it would mean that the individual that you receive care from is also the individual that you would give care to. The main issue that was found with this topology was the lack of connectivity between individuals in the network, resulting in an unequal sharing of benefits. Individuals within the network with a pre-existing low level of motivation or positivity were too isolated and could not feel flow on benefits from individuals with naturally higher levels of positivity and motivation, instead being stuck in a cycle where they were primarily influenced by their existing feelings.
