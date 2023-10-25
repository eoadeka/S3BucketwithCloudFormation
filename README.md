# Infrastructure as Code with AWS CloudFormation

Learn about Infrastructure as Code (IaC) by creating CloudFormation Templates. Start with simple templates to provision AWS resources like Amazon S3 buckets. Progress to more complex templates that deploy multi-tier applications with networking, security and autoscaling configurations.

## SERVICES
    - CloudFormation: provides a common language to describe and provision all the infrastructure resources in your environment in a safe, repeatable way.

## USE CASES FOR THE SERVICE
    - Infrastructure Management: CloudFormation

## Features
    - Stacks:
        A stack is a collection of AWS resources that you can manage as a single unit.
    - StackSets:
        StackSets enables you to create, update or delete stacks across multiple accounts and regions with a single operation
    - Changesets:
        Changesets allow you to preview how proposed changes to a stack might impact your running resources, making changes to your stack only when you decide
    - Driftdetection
        Run drift detection to identify configuration changes between your live resources and the template. Drifts will be detected on stacks and resources

## STEPS
1. Log in to the AWS Management Console.
2. Navigate to CloudFormation
3. Navigate to Stacks
    - Step 1: Create Stack
        - Click Create Stack Dropdown
        - Choose with new resources (standard)
        - Prerequisite – Prepare template
            - Choose "Template is ready"
        - Specify template
            - Choose "Upload a template file" as Template source
            - Upload a template file
        - Next
    - Step 2: Specify stack details
        - Enter stack name as ChallengeStack
        - Parameters
            - The Bucket name should be "ChallengeBucket" as set in template file
        - Next
    - Step 3: Configure stack options
        - Leave as is
        - Next
    - Step 4: Review ChallengeStack
        - Submit
4. Track Stack events and status

## RESULTS