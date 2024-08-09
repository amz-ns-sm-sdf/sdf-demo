- name: calling api      
      run: suitecloud account:savetoken --account ${{ inputs.NETSUITE_ACCOUNT_ID }} --authid ${{ inputs.NETSUITE_AUTH_ID }} --tokenid ${{ inputs.NETSUITE_TOKEN_ID }} --tokensecret ${{ inputs.NETSUITE_TOKEN_SECRET }}
      shell: bash
