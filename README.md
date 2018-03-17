# Ansible Role: Google Cloud Platform SDK
[![Build Status](https://travis-ci.org/brentwg/ansible-role-gcloud-sdk.svg?branch=master)](https://travis-ci.org/brentwg/ansible-role-gcloud-sdk)

This role installs the Google Cloud Platform SDK for Linux.

## Requirements  

None.  

## Role Variables 
Sane and opinionated defaults have been provided for creating YUM and APT repositories. See `defaults/main.yml` for more information.  

## Dependencies

None.  

## Sample Playbook
```
- hosts: all
  
  roles:
    - brentwg.gcloud-sdk
```
