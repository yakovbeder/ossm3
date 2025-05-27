# ossm3

This repository contains resources, manifests, and documentation for deploying and managing OpenShift Service Mesh 3 (OSSM3) on OpenShift clusters.

## Contents

- Example YAML manifests for OSSM3 components
- Configuration guides and best practices
- Integration examples with other OpenShift workloads

## Repository Structure

- **mesh/**: Contains manifests and configuration files for deploying and managing the OpenShift Service Mesh control plane and related resources.
- **otel/**: Contains resources for deploying and configuring OpenTelemetry components for observability and tracing within the mesh.
- **tempo/**: Contains manifests and configuration for integrating and deploying Tempo, a distributed tracing backend, with OSSM3.

## Usage

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd ossm3
   ```
2. Apply the manifests as needed to your OpenShift cluster.

## Documentation

Refer to the [OpenShift Service Mesh documentation](https://docs.openshift.com/container-platform/latest/service_mesh/v2x/ossm-about.html) for detailed information.

## Support

For issues or questions, please open an issue in this repository.
