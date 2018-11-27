Test phat

let armTemplateUri = 'https://raw.githubusercontent.com/khoi-thinh/hpc-edit/master/Nikko-HPC-Template.json';
let deployLink = `https://portal.azure.com/#create/Microsoft.Template/uri/${encodeURIComponent(armTemplateUri)}`;
window.location = deployLink;
