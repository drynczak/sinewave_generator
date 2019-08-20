# sinewave_generator
Sinewave_generator zawiera aplikację, która generuje sygnał sinusoidalny o podanej przez użytkownika częstotliwości próbkowania, 
częstotliwości sygnału, amplitudzie oraz czasie trwania. 
Składa się z funkcji odpowiedzialnych za wygenerowanie sinusa, przekonwertowanie tablicy z wartościami na bajty
oraz zapisanie pliku wave. Okazało się, że błędny zapis do wave'a jest spowodowany złym headerem, 
który w aktualnej wersji aplikacji został poprawiony i napisany krok po kroku z uwzględnieniem kolejności bajtów
w odpowiednich częściach pliku. 
Fragment kodu generujący plik zostanie wykorzystany w docelowej aplikacji nagrywającej sygnał.
