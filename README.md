# CLOUD COMPUTING

List of resources, tools, links around cloud computing topics - mainly AWS, Azure, GCP.

# AWS
## NETWORKING
### AWS Direct Connect

#### Opis

Serwis, który ułatwia zestawienie dedykowanego połączenia pomiędzy serwerownią a AWS. 

#### Podobne Usługi

#### Ważne Linki

- FAQ - https://aws.amazon.com/directconnect/faqs/
- Product Details - https://aws.amazon.com/directconnect/details/
- CLI Reference - http://docs.aws.amazon.com/cli/latest/reference/directconnect/index.html
- Dokumentacja - http://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html
- API Reference - http://docs.aws.amazon.com/directconnect/latest/APIReference/Welcome.html

#### Lab
#### Ceny

- Dwa składniki:
— Wielkość portu po stronie AWS
— Transfer danych wychodzący z AWS

-  Przykład dla Frankfurt:
— Port 100 Mb/s po stronie AWS
— Kolokacja portu w CE Colo Prague to/from EU Central (Frankfurt) Region
— Wysyłamy z AWS 400 GB danych miesięcznie do lokalnego Data Center
— Port - $0.06/hour
— Transfer - $0.030/GB
— Suma - (30 * 24 * $0.06) + (400 * $0.030) = $43,2 + $12 = $55,2

- Ważne aspekty związane z cenami:
— Dodatkowo musimy pokryć koszt łącza po swojej stronie i połączenia z kolokacją


#### Video
#### Ważne

- Chcesz mieć redundancję, to potrzebujesz drugi AWS Direct Connect link (cena x 2) lub VPN Connection
- AWS Direct Connect nie daje Service Level Agreement (SLA)
- AWS rozgłasza przez dany link wszystkie adresacji z danego regionu
- Możliwe jest dodanie drugiej sesji BGP dla ruchu IPv6


#### Historia

- 2017.10.10 - Now you can configure Amazon side private Autonomous System Number for your Virtual Private Gateway - https://aws.amazon.com/about-aws/whats-new/2017/10/now-you-can-configure-amazon-side-private-autonomous-system-number-for-your-virtual-private-gateway/
- 2017.09.12 - Announcing New AWS Direct Connect Location in Houston, TX - https://aws.amazon.com/about-aws/whats-new/2017/
- 2017.09.12 - Announcing New AWS Direct Connect Location in Canberra, Australia - https://aws.amazon.com/about-aws/whats-new/2017/
- 2017.08.31 - Announcing New AWS Direct Connect Location in Boston, MA - https://aws.amazon.com/about-aws/whats-new/2017/08/announcing-new-aws-direct-connect-location-in-boston-ma/
- 2017.07.29 - AWS Direct Connect now provides Amazon CloudWatch Monitoring - https://aws.amazon.com/about-aws/whats-new/2017/06/aws-direct-connect-now-provides-amazon-cloudwatch-monitoring/
- 2017.06.27 - Announcing New AWS Direct Connect Locations in Kuala Lumpur and Seoul - https://aws.amazon.com/about-aws/whats-new/2017/06/announcing-new-aws-direct-connect-locations-in-kuala-lumpur-and-seoul/
- 2017.05.31 - Announcing New AWS Direct Connect Locations in Atlanta, Columbus and Toronto - https://aws.amazon.com/about-aws/whats-new/2017/05/announcing-new-aws-direct-connect-locations-in-atlanta-columbus-and-toronto/
- 2017.05.23 - Announcing New Direct Connect Locations in Marseille, France and Warsaw, Poland - https://aws.amazon.com/about-aws/whats-new/2017/05/announcing-new-direct-connect-locations-in-marseille-france-and-warsaw-poland/
- 2017.05.21 - Announcing New Direct Connect Locations in Philadelphia, PA and Newark, NJ - https://aws.amazon.com/about-aws/whats-new/2017/05/announcing-new-direct-connect-locations-in-philadelphia-pa-and-newark-nj/
- 2017.03.28 - Announcing New Direct Connect Locations in Munich, Prague, Berlin, and Zurich - https://aws.amazon.com/about-aws/whats-new/2017/03/announcing-new-aws-direct-connect-location-in-munich-prague-berlin-zurich/
- 2017.03.10 - AWS Direct Connect joins growing list of HIPAA-eligible services from AWS! - https://aws.amazon.com/about-aws/whats-new/2017/03/aws-direct-connect-joins-growing-list-of-hipaa-eligible-services-from-aws/
- 2017.03.08 - Announcing New Direct Connect Location in Vienna - https://aws.amazon.com/about-aws/whats-new/2017/03/announcing-new-aws-direct-connect-location-in-vienna/
- 2017.02.28 - AWS Direct Connect enables Link Aggregation Group for additional AWS regions - https://aws.amazon.com/about-aws/whats-new/2017/02/aws-direct-connect-enables-link-aggregation-group-for-additional-aws-regions/
- 2017.02.13 - AWS Direct Connect announces support for Link Aggregation - https://aws.amazon.com/about-aws/whats-new/2017/02/aws-direct-connect-announces-support-for-link-aggregation/
- 2011.08.03 - Announcing AWS Direct Connect
 - https://aws.amazon.com/about-aws/whats-new/2011/08/03/Announcing-AWS-Direct-Connect/
