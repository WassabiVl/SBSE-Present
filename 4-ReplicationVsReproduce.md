# Reproducibility vs Replication


## Five elements in SE experimentation (Gómez et al. [11])

1. **Site** 
2. **Experimenters**
3. **Apparatus** 
4. **Operationalizations** 
5. **Population Properties** 

::: notes

Definitions

1. **<u>Site:</u>** Represents the place where the replication is conducted. Exp. Computer
2. **<u>Experimenters:</u>**  The experimenters in a replication can be the same people as participated in the reference experiment, different experimenters or a mixture of both
3. **<u>Apparatus:</u>** design, instruments, forms, materials, experimental objects and procedures used to run an experiment 
4. **<u>Operationalizations:</u>**  The cause operationalizations represent the treatments to be evaluated in the experiment (independent variables) whereas the effect operationalizations represent the response variables (dependent variables) that we use to measure the effects of the treatments.
5. **<u>Population Properties:</u>** subjects participating/experimental objects

**<u>Reproducibility:</u>** is the closeness of the agreement between the results of measurements of the same measurand carried out with same methodology described in the corresponding scientific evidence. [6]

<u>**Reproducibility**</u>  the ability of a study to be reproduced, in whole or in part, by an independent research team. partially because being able to repeat specific steps of a study, while changing others, is the basis for accurate benchmarking of research methodologies and tools, and to detect intermediate steps subject to improvement [7]

**<u>Replication:</u>** An attempt to reproduce an empirical study in order to further validate its findings, or the successful outcome of such an attempt.
Replication is often proposed as one of the major avenues to achieve, or ensure, greater validity in software engineering research. [10] 

:::

## Functions/Purposes of a replication in SE [11]

1. Control for Sampling Error
2. Control for Artefactual Results 
3. Determine Limits for Operationalizations
4. Determine Limits in the Population Properties.

::: notes

1. Control for Sampling Error
	- if the 5 elements are kept unchanged, the purpose is verify that the results output by the reference experiment are not chance outcomes 
2. <u>Control for Artefactual Results</u> 
	- if site, experimenters or apparatus is changed, the purpose verify that the observed results are not artefactual, that is, they reflect reality and are not a product of the site, experimenters or the apparatus setup
3. <u>Determine Limits for Operationalizations</u>
	- if Operations Change, this determine the range of variation of the treatments (independent variables) and the measures (independent variables) used to measure the effects of the treatments.
4. <u>Determine Limits in the Population Properties.</u>
	- If the population properties changes
	- the purpose of this replication is to determine the types of subjects or the types of experimental objects to which the results of the replication can be generalized.

:::

## 6 Best Practices for Software Replication and Reproducibility (Widder et al. [16])

   1. **Deliberate Design**
   2. **Documentation**
   3. **Use Existing Components**
   4. **Use a Version Control System**
   5. **Testing**
   6. **Public Release**

::: notes

1. **Deliberate Design**
      1. A  process  to  determine  requirements  for  the system, and plan what to build and how to build it.
      2. the interface should be reusable and thus easier to reproduce
   2. **Documentation**
      1. Documentation is material which teaches others about  the  purpose  of,  correct  usage  of,  or  suggestions  for extending or modifying systems.
      2. Documenting code should explains how to reproduce results from code
   3. **Use Existing Components**
      1. The usage, when possible, of existing code, such as libraries, packages, or frameworks to build a system. 
      2. Existing and vetted software components are less likely to have errors, and no need for reinventing the wheel
   4. **Use a Version Control System**
      1. Version   control   systems   help   teams   track changes to code and data, and make undoing changes easier 
      2. backup, and facilitate public release by easing code sharing between researchers
   5. **Testing**
      1. Software   testing   is   a   manual   or   automatic process  to  ensure  that  the  system  under  test  meets  given requirements and other quality attributes.
      2. test cases, allow others to understand new code better, thus assisting external replicability
   6. **Public Release**
      1. Publicly  releasing  code  on  hosting  sites  such as  GitHub,  or  even  as  part  of  a  formal  academic  review  and publication process.
      2. Public release of code allows others to critique and replicate the original experiment using the original code

:::

## Barriers (summary) [16]:

1.  Tool based barriers
2.  Self efficacy barriers
3.  Training-related barriers
4.  Team related barriers

##  Solutions [16]: 

1. Increased education
2. adaption of existing tools
3. More Incentives
