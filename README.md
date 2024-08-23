# 🤫


[Relative -> Absolute](javascript:(function(){document.querySelectorAll('relative-time').forEach(function(elem){var newElem=document.createElement('span');var isoDate=new Date(elem.getAttribute('datetime'));var options={year:'numeric',month:'long',day:'2-digit',hour:'2-digit',minute:'2-digit',second:'2-digit',hour12:!1};var formattedDate=isoDate.toLocaleString('default',options);Array.from(elem.attributes).forEach(attr=>newElem.setAttribute(attr.name,attr.value));newElem.textContent=formattedDate;elem.parentNode.replaceChild(newElem,elem)})})())



