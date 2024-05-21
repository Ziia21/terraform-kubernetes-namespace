# Usage

### Please copy paste below code
```
module "testns" {
  source = "Ziia21/namespace/kubernetes"
  name   = "testns"
  annotations = {
    new = "application"
  }
  labels = {
    createdby = "Ziia21"
  }
}
```