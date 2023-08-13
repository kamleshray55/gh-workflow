i want to run `Upload test report` step when `Test code` step fail

- name: Test code
  run: npm run test - name: Upload test report
  uses: actions/upload-artifact@v3
  with:
  name: test-report
  path: test.json
