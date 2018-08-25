---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AuthorizeSecurityGroupEgress (EC2-VPC only):
    get:
      summary: Authorize Security Group Egress ( E C2- V P C only)
      description: '[EC2-VPC only] Adds one or more egress rules to a security group
        for use with a VPC.'
      operationId: authorizesecuritygroupegress-ec2vpc-only
      x-api-path-slug: actionauthorizesecuritygroupegress-ec2vpc-only-get
      parameters:
      - in: query
        name: CidrIp
        description: The CIDR IPv4 address range
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: FromPort
        description: The start of port range for the TCP and UDP protocols, or an
          ICMP/ICMPv6 type number
        type: string
      - in: query
        name: GroupId
        description: The ID of the security group
        type: string
      - in: query
        name: GroupName
        description: '[EC2-Classic, default VPC] The name of the security group'
        type: string
      - in: query
        name: IpPermissions.N
        description: A set of IP permissions
        type: string
      - in: query
        name: IpProtocol
        description: The IP protocol name (tcp, udp, icmp) or number      (see Protocol
          Numbers)
        type: string
      - in: query
        name: SourceSecurityGroupName
        description: '[EC2-Classic, default VPC] The name of the source security group'
        type: string
      - in: query
        name: SourceSecurityGroupOwnerId
        description: '[EC2-Classic] The AWS account number for the source security
          group, if the source security group is in a different account'
        type: string
      - in: query
        name: ToPort
        description: The end of port range for the TCP and UDP protocols, or an ICMP/ICMPv6
          code number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=AuthorizeSecurityGroupIngress:
    get:
      summary: Authorize Security Group Ingress
      description: Adds one or more ingress rules to a security group.
      operationId: authorizesecuritygroupingress
      x-api-path-slug: actionauthorizesecuritygroupingress-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: GroupDescription
        description: A description for the security group
        type: string
      - in: query
        name: GroupName
        description: The name of the security group
        type: string
      - in: query
        name: VpcId
        description: '[EC2-VPC] The ID of the VPC'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
---