# Helloworld
## How to push local code to remote?
1.  git clone https://github.com/rM4moon/helloworld.git
      -- better to config the username/email for the committ message.
      -- better to config the git editor to vim.
2.  if (input username/passwd):
      add "credential" at file .git/config 
    else if(ssh)
      -- generate ssh pub key and config to github setting. 
      -- git remote set-url **.git. 
3.  git push origin HEAD 
