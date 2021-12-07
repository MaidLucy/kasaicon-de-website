---
layout: default
title: Kontakt & Das sind wir
---

# Kontakt & Das sind wir

Erreichen könnt ihr uns ganz einfach unter [kasaicon@yahoo.com](mailto:kasaicon@yahoo.com) oder auf Instagram ([kasaicon.real](instagram.com/kasaicon.real/)), Facebook (kasaicon.real) und Twitter (kasaiconRGB). <br>
Händler, Künstler, Showacts, Panals und Workshops sollten bitte über die Formulare ausgefüllt werden. 

Wir antworten auf jede Anfrage so schnell wie es uns möglich ist. 

## Das Team

Es ist nicht gängig, dass sich die Organisatoren einer Convention vorstellen. 
Aber wir wollen alle gemeinsam eine persönliche Veranstaltung erleben, da gehört es auch dazu, dass ihr unsere Gesichter und unser Namen kennt:

{% for member in site.team_members %}
<div class="row">
<div class="col-xl-6">
<div class="row"><div class="col-md-4"> <b> Name:                          </b></div><div class="col-md-8"> <p>{{ member.name }}             </p></div> </div>
<div class="row"><div class="col-md-4"> <b> Baujahr:                       </b></div><div class="col-md-8"> <p>{{ member.year }}             </p></div> </div>
<div class="row"><div class="col-md-4"> <b> Das organisiere ich für euch:  </b></div><div class="col-md-8"> <p>{{ member.orga_role }}        </p></div> </div>
<div class="row"><div class="col-md-4"> <b> Ich cosplaye seit:             </b></div><div class="col-md-8"> <p>{{ member.cosplaying_since }} </p></div> </div>
<div class="row"><div class="col-md-4"> <b> Hauptfandom:                   </b></div><div class="col-md-8"> <p>{{ member.fandoms }}          </p></div> </div>
<div class="row"><div class="col-md-4"> <b> Das mache ich Hauptberuflich:  </b></div><div class="col-md-8"> <p>{{ member.occupation }}       </p></div> </div>
<div class="row"><div class="col-md-4"> <b> Da bin ich online zu finden:   </b></div><div class="col-md-8"> <p>{{ member.online_accounts }}  </p></div> </div>
<div class="row"><div class="col-md-4"> <b> Das muss man über mich wissen: </b></div><div class="col-md-8">    {{ member.content }}          </div> </div>
<div class="row"><div class="col-md-4"> <b> Meine Schwächen:               </b></div><div class="col-md-8"> <p>{{ member.shortcommings }}    </p></div> </div>
</div>
<div class="col-xl-6 bg-dark">
<img src="{{ member.image }}" alt="Foto von {{ member.name }}" class="text-white">
</div>
</div>
<br>
{% endfor %}
