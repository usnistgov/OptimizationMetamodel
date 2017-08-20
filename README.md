
# OptimizationMetamodel

This repository contains a Papyrus project containing the NIST Optimization Metamodel. A *metamodel* is a model of
a modeling language possessing sufficient detail to serve as a storage form for instances of the metamodel (models).
This definition is roughly compatible with how the Object Management Group (standards organization that created UML)
uses the term. The modeling language that this metamodel models is the Optimization Programming Language (OPL), an
algebraic modeling language. [1] The intended purpose of this model is to facilitate the automated composition of
optimizations problems, though it might serve other purposes as well. If you use it, we would appreciate a note
describing your plans; we are planning on enhancing the work. 

Details of the model are provided in a paper found in the doc subdirectory.

Declarations:
![decls](https://github.com/usnistgov/OptimizationMetamodel/blob/master/doc/images/OM-declarations.jpg)

Expressions:
![exprs](https://github.com/usnistgov/OptimizationMetamodel/blob/master/doc/images/OM-expressions.jpg)

Operators:
![ops](https://github.com/usnistgov/OptimizationMetamodel/blob/master/doc/images/OM-operators.jpg)

## Installation

You can clone this repository anywhere, then in Papyrus do File -> Import -> "Existing Project into Workspace".
From the dialog that appears, select the directory; it will load the project without copying files into your papyrus workspace. The name of the Eclipse project created is OptimizationMM.

## References

[1] Pascal Van Hentenryck, *The OPL Optimization Programming Language*, MIT Press, 1999. ISBN-10: 0262720302


## Disclaimer
The use of any software or hardware by the project does not imply a recommendation or endorsement by NIST.

The use of the project results in other software or hardware products does not imply a recommendation or endorsement by NIST of those products.

We would appreciate acknowledgement if any of the project results are used, however, the use of the NIST logo is not allowed.

NIST-developed software is provided by NIST as a public service. You may use, copy and distribute copies of the software in any medium, provided that you keep intact this entire notice. You may improve, modify and create derivative works of the software or any portion of the software, and you may copy and distribute such modifications or works. Modified works should carry a notice stating that you changed the software and should note the date and nature of any such change. Please explicitly acknowledge the National Institute of Standards and Technology as the source of the software.

NIST-developed software is expressly provided “AS IS.” NIST MAKES NO WARRANTY OF ANY KIND, EXPRESS, IMPLIED, IN FACT OR ARISING BY OPERATION OF LAW, INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTY OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT AND DATA ACCURACY. NIST NEITHER REPRESENTS NOR WARRANTS THAT THE OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT ANY DEFECTS WILL BE CORRECTED. NIST DOES NOT WARRANT OR MAKE ANY REPRESENTATIONS REGARDING THE USE OF THE SOFTWARE OR THE RESULTS THEREOF, INCLUDING BUT NOT LIMITED TO THE CORRECTNESS, ACCURACY, RELIABILITY, OR USEFULNESS OF THE SOFTWARE.

You are solely responsible for determining the appropriateness of using and distributing the software and you assume all risks associated with its use, including but not limited to the risks and costs of program errors, compliance with applicable laws, damage to or loss of data, programs or equipment, and the unavailability or interruption of operation. This software is not intended to be used in any situation where a failure could cause risk of injury or damage to property. The software developed by NIST employees is not subject to copyright protection within the United States.


