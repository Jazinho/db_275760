Teoria kompilacji i kompilatory 2017 - Projekt
===============================================

By uruchomić projekt należy:

  1. Zainstalować VirtualBox-a.
  2. Zainstalować Vagrant-a.
  3. Ściągnąć sobie to repozytorium.
  4. Otworzyć jego katalog w konsoli i wykonać poniższe polecenia:
  5. `vagrant up` - żeby automatycznie ściągnąć, uruchomić i skonfigurować maszynę wirtualną z Ubuntu i zainstalować na nim OpenJDK i GCC.
  6. `vagrant ssh` - żeby zalogować się do maszyny. Dalsze polecenia wykonywane będą na maszynie.
  7. `cd /vagrant` - żeby przejść do katalogu projektu (automatycznie zsynchronizowanego).
  8. `projects/sample/bin/build` - żeby skompilować przykładowy projekt.
  9. `bin/test projects/sample` - żeby wykonać jego testy (patrz niżej).