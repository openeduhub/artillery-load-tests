# Artillery Load Tests

Runs load tests against web services.

## Usage

```sh
# Install dependencies
npm install

# Run a test
npm run artillery -- --config tests/config/<config>.yml tests/scenarios/<scenario>.yml
# Example
npm run artillery -- --config tests/config/mild-load.yml tests/scenarios/wlo.yml

# Generate html report for last test run
npm run report
```
