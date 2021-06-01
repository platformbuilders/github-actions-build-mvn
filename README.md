# Build

GitHub action used to build aplications using MVN

## Inputs

There are no inputs for this GitHub action

## Outputs

There is no outputs for this action

## Example usage

```yaml
      # Example using this actions
      - name: MVN Package
        uses: platformbuilders/github-actions-build-mvn@master
```

## How to send updates?
If you wants to update or make changes in module code you should use the **develop** branch of this repository, you can test your module changes passing the `@develop` in module calling. Ex.:

```yaml
      # Example using this actions
      - name: MVN Package
        uses: platformbuilders/github-actions-build-mvn@develop
```
After execute all tests you can open a pull request to the master branch. 