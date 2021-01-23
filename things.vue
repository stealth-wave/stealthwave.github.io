js:

function lightmode() {
  document.documentElement.classList.add("light") // this will enable light mode
  document.documentElement.classList.remove("light") // this will DISABLE lightmode=
}


css:

.light #Hire {
  /* css for #Hire in light mode */
}

#Hire {
  /* css for #Hire in not light mode */
}