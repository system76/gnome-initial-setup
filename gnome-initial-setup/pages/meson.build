pages = [
   'account',
   'appearance',
   'language',
   'keyboard',
   'network',
   'timezone',
   'privacy',
   'goa',
   'password',
   'summary',
]

if libmalcontent_dep.found() and libmalcontent_ui_dep.found()
  pages += 'parental-controls'
endif

foreach page: pages
    subdir (page)
endforeach
