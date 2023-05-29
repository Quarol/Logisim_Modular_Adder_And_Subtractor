# Logisim_Modular_Adder_And_Subtractor

Jest to układ wykonujący dodawanie i odejmowanie dla m=1 i n=4.
Aby przetestować czy wyniki dla wszystkich kombinacji liczb wejściowych mieszczących się w dziedzinie [0, m-1] są poprawne, należy skorzystać z opcji "Test Vector..." w zakładce "Simulate":
![image](https://github.com/Quarol/Logisim_Modular_Adder_And_Subtractor/assets/59970980/838d553f-ec7e-46b0-80d6-7b4acaf913e9)

Należy wybrać plik tekstowy z nagłówkami o pasujących etykietach oraz oczekwianych wartości wejść i wyjść.  
W folderze test_samples znajdują się trzy pliki tekstowe:  
- addition_vectors.txt - plik z rezultatami tylko dla operacji dodawania (121 wierszy nie licząc nagłówka)
- subtraction_vectors.txt - plik z rezultatami tylko dla operacji odejmowania (121 wierszy nie licząc nagłówka)
- all_vectors.txt - plik dla wszystkich operacji (242 wiersze nie licząc nagłówka)

Liczba 121 wynika z tego, że możemy mieć 11\*11 kombinacji dla każdej operacji, ponieważ w przedziale [0, m-1] = [0, 10] mamy 11 liczb.
