# Domain Parking: Largely Present, Rarely Considered!

Authors: TBA

## Abstract

Domain parking typically involves leveraging advertisements to generate revenue on otherwise inactive domain names. Their content is rarely of real value to users and tends to be highly similar across parked domains. They have commonalities beyond content alone: parked domains can share hosting and DNS infrastructure. Parking rarely receives special treatment in existing studies (e.g., content analyses or infrastructure concentration studies). While the presence and possible bias introduced by parked pages is sometimes acknowledged in studies, the studies still treat parked domains as any other, either because differentiation is infeasible, or because doing so is considered out-of-scope.

We argue that the impact of parked domains on analyses regarding the current state and future development of the Internet should not be overlooked. In this paper, we motivate this argument through quantification, and take steps towards helping other researchers identify parked domains.

We systematically collect a list of 82 parking services and develop DNS-based indicators to help identify parked domains. We next quantify the presence of parked domains, using large-scale DNS data containing hundreds of millions of registered domain names, representative for a significant part of the global DNS namespace. Overall, we pinpoint 60M parked domains, which is a significant percentage of all names under consideration (23 %). These findings demonstrate that the effect of parked pages is potentially pronounced. We also break down into the various parking services and DNS zones. This helps us demonstrate and further discuss the effect that domain parking can have on research and Internet consolidation.

## Parking Services

Our definitions for the 82 parking services can be found in the following `json` file:

[parking_services.json](https://tma22-parking.github.io/parking_services.json)
