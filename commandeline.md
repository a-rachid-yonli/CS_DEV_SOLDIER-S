exercice 1
cd ~
mkdir cli_tmp
touch cli_tmp / je_suis_dans_tmp.txt
cd cli_tmp -> touchez in_cli_tmp.html
mkdir in_cli_tmp
rm je_suis_dans_tmp.txt
cd .. -> rm -r cli_tmp
mkdir -p grand_parent/parent/gran_frere/grande_soeur/ami/connaissances
cd grand_parent/parent/grand_frere 
touch bachir.xls
mv bachir.xls /grande_soeur/ami 
cp -r ami ../../parent 
rm ../ami bachir.txt
pwd
cd ~
rm -r cli_tmp "" "le dossier cli_tmp a ete deja supprimmer depuis la question 6" ""

exercice 2

pwd 
ls
mkdir conteneur
cd conteneur -> touch "voitures.txt" "ustensiles.txt" "electronique.txt"
mkdir voitures -> cd voitures -> touch mes_voitures.txt "" j'ai creer le dossier voiture maintenant car il n'y avait pas ca au début de l'exo "" "
echo "benz toyota honda"> voitures.txt
cd .. -> mkdir ustensiles -> cd ustensiles "" "j'ai creer le dossier ustensiles car il n'existe pas au début de l'exo" ""
touch cuisine.txt -> echo "cuillere fourchette assiette"> cuisine.txt
cat cuisine.txt
cd .. -> ls -alt

exercice 3

pwd
ls
mkdir -p actualites/politiques
mkdir actualités/politiques elections
touch actualités/politique/elections / candidat.txt -> echo "yonli abdoul rachid"> candidat.txt
cd actualités -> mkdir buzz

exercice 4

pwd -> desktop
touch .configuration.txt
ls -a
mkdir -p creation/crayons
touch creation/crayons couleurs.txt
cp creation/couleur couleurs.txt colours.txt 
cd creation -> touch gomme.txt
mv gomme.txt crayons 
cd ~
cd desktop/exercices /exercice4 /creation

exercice 5

mkdir ma_classe
touch mes_camarades.txt -> echo "rachid abdoul omar wahab abdoul"> mes_camarades.txt
cat mes_camarades.txt
touche .surveillant.css
ls -a 
rm .surveillant.css
rm -r ma_classe 

exercice 6

/ usr / bin / ruby ​​-e "$ (curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brasser installer asciiquarium
asciiquarium

exercice 7

brew install sl
sl

exercice 8

installer brew cmatrix
cmatrix




