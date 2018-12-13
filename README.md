# huntestrator
This repo contains automations, playbooks, and content for operationalizing threat hunting at scale.  This is currently an ALPHA release, with the following known and major deficiencies:

1) The default huntingcontent.json is by no means complete.  The framework maps to the RSA Network Hunting labyrinth (although you can make it whatever you'd like) but does not have each hunting task query defined or defined well just yet.
2) The influencers are experimental and need updated logic before they will be very useful.
3) This only works out of the box with NetWitness as your SIEM/hunting platform currently.  Eventually it will be more modular across other systems without having to re-code anything.

Details usage and configuration instructions can be found here:  <Link to RSA Community>
  
Note that for this to work in your NWO (or Demisto) + NetWitness environment, you'll have to make a few modifications to the huntingcontentmodel.json file to point it at your NetWitness servers, and possibly your own huntingcontent.json file if you don't want to use the default (and incomplete) one currently in this repo.
