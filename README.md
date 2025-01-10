@relation pisa_dataset

@attribute student_id numeric
@attribute country string
@attribute gender {male, female}
@attribute math_score numeric
@attribute reading_score numeric
@attribute science_score numeric
@attribute school_type {public, private}

@data
1, Brazil, male, 420, 380, 400, public
2, Brazil, female, 480, 520, 450, private
3, USA, female, 600, 590, 610, private
4, USA, male, 550, 530, 560, public
5, China, female, 700, 720, 710, private

