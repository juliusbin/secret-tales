# secret-tales
The magic tales of hidden software secrets

GitHub push protection enforced

```sh
> git push origin main:main
remote: error: GH013: Repository rule violations found for refs/heads/main.        
remote: 
remote: - GITHUB PUSH PROTECTION        
remote:   —————————————————————————————————————————        
remote:     Resolve the following violations before pushing again        
remote: 
remote:     - Push cannot contain secrets        
remote: 
remote:             
remote:      (?) Learn how to resolve a blocked push        
remote:      https://docs.github.com/code-security/secret-scanning/working-with-secret-scanning-and-push-protection/working-with-push-protection-from-the-command-line#resolving-a-blocked-push        
remote:             
remote:             
remote:       —— GitHub Personal Access Token ——————————————————————        
remote:        locations:        
remote:          - commit: d2991da1bfe0da68db9c484549c7aaa47d194083        
remote:            path: .npmrc:5        
remote:             
remote:        (?) To push, remove secret from commit(s) or follow this URL to allow the secret.        
remote:        https://github.com/juliusbin/secret-tales/security/secret-scanning/unblock-secret/3141bEQ3e6L1odwInDlJmGyLmHZ        
remote:             
remote: 
remote: 
To https://github.com/juliusbin/secret-tales
 ! [remote rejected] main -> main (push declined due to repository rule violations)
error: failed to push some refs to 'https://github.com/juliusbin/secret-tales'
```