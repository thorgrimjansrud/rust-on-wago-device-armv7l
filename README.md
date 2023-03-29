# rust-on-wago-device-armv7l


# RUST
Homepage:  
https://forge.rust-lang.org/infra/other-installation-methods.html  

1. Get the install script   
curl https://sh.rustup.rs -sSf | sh  

ERROR: curl: (60) SSL certificate problem: unable to get local issuer certificate

Manually download script!


chmod +x rustup-init  
./rustup-init  
  
 </br>  </br> 
 Result:  
 </br> 

***  
Welcome to Rust!

This will download and install the official compiler for the Rust
programming language, and its package manager, Cargo.

Rustup metadata and toolchains will be installed into the Rustup
home directory, located at:

  /root/.rustup

This can be modified with the RUSTUP_HOME environment variable.  

The Cargo home directory is located at:  

  /root/.cargo  

This can be modified with the CARGO_HOME environment variable.  

The cargo, rustc, rustup and other commands will be added to  
Cargo's bin directory, located at:  

  /root/.cargo/bin  

This path will then be added to your PATH environment variable by  
modifying the profile file located at:  

  /root/.profile  

You can uninstall at any time with rustup self uninstall and  
these changes will be reverted.  

Current installation options:  


   default host triple: armv7-unknown-linux-gnueabihf  
     default toolchain: stable (default)  
               profile: default  
  modify PATH variable: yes  

1) Proceed with installation (default)  
2) Customize installation  
3) Cancel installation  

***
Tryied option 1

error: component download failed for rustc-armv7-unknown-linux-gnueabihf: could not download file from 'https://static.rust-lang.org/dist/2023-03-28/rustc-1.68.2-armv7-unknown-linux-gnueabihf.tar.xz' to '/root/.rustup/downloads/f4d11a7aaa83aeb52c1fe95393939c049385de5956282f1732031961e2806927.partial'
root@EC752-492524:/home/admin/rust  

NO SPACE LEFT ??  
Cleaning up.. 659MB space left..try again..  
Failed again same........   
 
 </br>  </br> 

Manually install tarball:

 </br>  </br> 
 
 Problem.. no space left.. tarball is 334MB...   
 Must try to boot from SD card to get more mem..  
  
 
 
 





