# apigee-hybrid-multiple-ingress

This repo contains a sample YAML file that will allow you to create multiple ingresses for [Apigee Hybrid](https://cloud.google.com/apigee/hybrid).

## Prerequisites

An Apigee Hybrid organization deployed and running on a k8s cluster. 

## Context
In some circumstances some customers may want to use multiple ingresses for their Apigee environments, so that all partners, for instance, are completely isolated from each other at a network level.

This configuration files will allow you to have multiple ingresses with different certs for each environment group:

 [IstioOperator.yaml](./IstioOperator.yaml)
 
 [overrides.yaml](./overrides.yaml)



