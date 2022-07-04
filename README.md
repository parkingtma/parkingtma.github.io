# Domain Parking: Largely Present, Rarely Considered!

Authors: Johannes Zirngibl, Steffen Deusch, Patrick Sattler, Juliane Aulbach, Georg Carle, and Mattijs Jonker

## Abstract

Domain parking typically involves leveraging advertisements to generate revenue on otherwise inactive domain names. Their content is rarely of real value to users and tends to be highly similar across parked domains. They have commonalities beyond content alone: parked domains can share hosting and DNS infrastructure. Parking rarely receives special treatment in existing studies (e.g., content analyses or infrastructure concentration studies). While the presence and possible bias introduced by parked pages is sometimes acknowledged in studies, the studies still treat parked domains as any other, either because differentiation is infeasible, or because doing so is considered out-of-scope.

We argue that the impact of parked domains on analyses regarding the current state and future development of the Internet should not be overlooked. In this paper, we motivate this argument through quantification, and take steps towards helping other researchers identify parked domains.

We systematically collect a list of 82 parking services and develop DNS-based indicators to help identify parked domains. We next quantify the presence of parked domains, using large-scale DNS data containing hundreds of millions of registered domain names, representative for a significant part of the global DNS namespace. Overall, we pinpoint 60 M parked domains, which is a significant percentage of all names under consideration (23 %) and identify up to 4 % of domains from top lists to be parked. These findings demonstrate that the effect of parked pages is potentially pronounced. We also break down into the various parking services and DNS zones. This helps us demonstrate and further discuss the effect that domain parking can have on research and Internet consolidation.

## Parking Services

Our definitions for the 82 parking services can be found in the following `json` file:

[parking_services.json](https://tma22-parking.github.io/parking_services.json)

The indicators can be used to identify parked domains based on DNS resolutions.
Depending on the service, either IP addresses, name servers or canonical names are used for identification.
Thus successfull detection requires A, AAAA, CNAME and NS queries.

## Parked Domains

We are happy to share parked domains based on regularly conducted scans of more than 300 M domains on request.
To request data, please send <a href="mailto:data-request@net.in.tum.de"> us an E-Mail</a> including your affiliation and why you want access to parked domains.

## Referencing our Work

If you are using collected parking service indicators or results from this work in your publication, please refer to it with the following reference [bib](https://tma22-parking.github.io/zirngibl2022prevalenceofparking.bib)

```
@inproceedings{zirngibl2022prevalenceofparking,
  author = {Zirngibl, Johannes and Deusch, Steffen and Sattler, Patrick and Aulbach, Juliane and Carle, Georg and Jonker, Mattijs},
  title = {Domain Parking: Largely Present, Rarely Considered!},
  booktitle = {Proc. Network Traffic Measurement and Analysis Conference (TMA) 2022},
  year = {2022},
  month = jun,
  month_numeric = {6}
}
```
