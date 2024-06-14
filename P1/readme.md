to set up a simple vm using vagrant  you can go to [`vagrant cloud`](https://app.vagrantup.com/boxes/search) and choose you prefered box, once chosen you can either take the vagrant file code or the cli command to init the vagrantfile with the required box configuration.

once the first step is done, and after installing vagrant into your machine you can run this command:
```bash
vagrant up
```

this will download the box, and set up all the requirements you set in the vagrant file

after setting the vms, if you had any customizations on the vagrant file you can run this command to apply those customizations:
```bash
vagrant provision
```

after all that is done you can either access the vm via the normal ssh method or use this command instead

```bash
# for one vm 
vagrant ssh
# for one from multiple vms
vagrant ssh <vmname>
```

those are the steps to make a vm with vagrant
