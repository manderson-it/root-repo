# Overview

This is the shared common RootSync that is added to all clusters. The purpose is to create a homoegenous cluster configuration so all clusters have the same users, CRDs, ClusterRoles, ClusterRoleBindings and common software (typically operator software)

## Warnings

Changes to files in this folder will cause ALL clusters using this primary root repo to update, the affected radius could be large, use
