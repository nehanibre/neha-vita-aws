# Virtual Private Cloud

It is virtual network dedicated to your aws account .It is at organisation level and can configure it.

-VPC has CIDR block that consist of IP adress range that decides EC2 service adresses.

-VPC consist of subnets.

   Subnets are of 2 types: 

   private:

   public:
   
   Subnets are avaliable in different Zone.

-subnet  consist of  route table  that  consist of Internet Gateway that helps to connect to internet.

-Security group is present in every subnets.

## Cloud watch

it monitors resources used eg.Ec2 ram,cpu and applications.

## Cloud trail 

track user activity

when we perform any action on AWS userinterface it is stored by cloud trail.

eg. if we stop aws instance then it will store username .

## Status check:

two types:

System :These checks monitor the AWS systems required to use this instance and ensure they are functioning properly.

instance:These checks monitor your software and network configuration for this instance.


