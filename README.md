% Changes to WEKA Format: SRG - November 1994
%  1. Boolean attributes changed from 1 and 0 to Enumerated attribute with
%       values {true and false}
%  2. Class Number (Attribute 18) changed to an Enumerated type with
%      values {1,2,3,4,5,6,7} 
%
% December 1997 - Changed class attribute values to semi-sensible names
%
% 1. Title: PISA and IDEB Brazil Database
%
% 2. Source Information
%    -- Creator: OpenAI
%    -- Donor: OpenAI Team
%              123 Innovation Road
%              Silicon Valley
%              California, USA
%              +1-800-1234567
%
% 3. Description: 
%    This dataset contains PISA test scores and IDEB (Education Development Index) for various states in Brazil.
%    The data includes information for 2018 and 2021.

@relation pisa_ideb_brasil

@attribute estado {SP, RJ, BA, MG} % Estado da Federação
@attribute ano {2018, 2021} % Ano de realização da avaliação
@attribute pisa_mat numeric % Nota PISA em Matemática
@attribute pisa_leit numeric % Nota PISA em Leitura
@attribute pisa_cien numeric % Nota PISA em Ciências
@attribute ideb numeric % Índice IDEB

@data
% A seguir, os dados de desempenho educacional de vários estados brasileiros, coletados pelo PISA e IDEB.
SP, 2018, 395, 400, 390, 5.6
RJ, 2018, 390, 385, 380, 5.2
BA, 2018, 370, 360, 350, 4.5
MG, 2018, 400, 405, 395, 5.8
SP, 2021, 405, 410, 400, 6.0
RJ, 2021, 395, 390, 385, 5.5
BA, 2021, 375, 365, 360, 4.8
MG, 2021, 410, 415, 405, 6.2



