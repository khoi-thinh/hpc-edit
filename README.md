Test phat

let armTemplateUri = 'https://raw.githubusercontent.com/khoi-thinh/hpc-edit/master/Nikko-HPC-Template.json';
let deployLink = `https://portal.azure.com/#create/Microsoft.Template/uri/${encodeURIComponent(armTemplateUri)}`;
window.location = deployLink;


<a href="https://azuredeploy.net/?repository=https://raw.githubusercontent.com/khoi-thinh/hpc-edit/master/Nikko-HPC-Template.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
