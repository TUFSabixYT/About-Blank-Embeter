# About-Blank-Embeter
//dosent work on every website still working on



javascript:(function(){var i, nd; function copyChildren(a,b){var i, nn; for(i=0;i<a.childNodes.length;++i) { nn = a.childNodes[i].cloneNode(true); if(nd.importNode) nn = nd.importNode(nn, true); b.appendChild(nn); } } nd=window.open().document; nd.open(); nd.close(); /*140681*/ copyChildren(document.getElementsByTagName("head")[0], nd.getElementsByTagName("head")[0]); copyChildren(document.body, nd.body);})();
