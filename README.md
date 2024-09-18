# neutral-single-nucleotide-polymorphisms-analysis

# О наборе данных

0. Rs_id (идентификатор SNP)
- Уникальный номер, присвоенный конкретному варианту нуклеотидной последовательности в базе данных, например, dbSNP.

1. ContigPositionStart_0_based (начальная позиция континга)
- Позиция начала варианта в континге, где 0 означает, что первая нуклеотидная позиция имеет индекс 0.

2. ContigPositionEnd_0_based (конечная позиция континга)
- Позиция конца варианта в континге, также с нумерацией с нуля.

3. GenomeBuild (версия сборки генома)
- Указывает на конкретную версию геномной сборки, используемую для аннотации данных.

4. mRNA_acc_version (доступный номер версии mRNA)
- Уникальный идентификатор для транскрипта мРНК, который может включать информацию о версии.

5. mRNA_start_position_0_based (начальная позиция мРНК)
- Позиция начала мРНК, где начинается кодирующая последовательность.

6. mRNA_end_position_0_based (конечная позиция мРНК)
- Позиция конца мРНК, где заканчивается кодирующая последовательность.

7. ReadingFrame_base_position_in_codon (позиция в кодоне в рамках рамки считывания)
- Указывает на положение нуклеотида в кодоне (0, 1 или 2).

8. MissenseAllele (аллель с изменением)
- Аллель, содержащий мутацию, которая меняет одну аминокислоту на другую в белке.

9. MissenseCodon (кодон, кодирующий изменённую аминокислоту)
- Кодон, который после мутации кодирует аминокислоту, отличающуюся от исходной.

10. ReferenceAllele (эталонный аллель)
- Аллель, который считается стандартным для данной позиции в геноме; используется для сравнения с другими аллелями.

11. ReferenceCodon (эталонный кодон)
- Кодон, который соответствует эталонному аллелю и кодирует аминокислоту до мутации.

12. AminoAcidPosition_0_based (позиция аминокислоты)
- Позиция аминокислоты в белке, где 0 обозначает первую аминокислоту.

# Предварительный анализ данных
Результаты:
- ContigPositionStart_0_based
![image](https://github.com/user-attachments/assets/027e8852-b331-46ec-854c-53b393f1aba4)

- ContigPositionEnd_0_based
![image](https://github.com/user-attachments/assets/e6d95259-599e-4572-b7c8-96016955bcc4)

- mRNA_start_position_0_based
![image](https://github.com/user-attachments/assets/9aea01da-b857-4c69-81fb-a8d4dedf1954)

- mRNA_end_position_0_based
![image](https://github.com/user-attachments/assets/e1aeeadc-ff18-4d38-be68-98673a6dbb5f)

- ReadingFrame_base_position_in_codon
![image](https://github.com/user-attachments/assets/f772fc10-0e71-4dc1-b0f6-66a48f3c7bbb)

- AminoAcidPosition_0_based
![image](https://github.com/user-attachments/assets/b8e9689b-c3d8-4c47-b6f1-a43defacf51b)



# Корреляционный анализ данных
Столбчатая диаграмма корреляций:
![image](https://github.com/user-attachments/assets/799ab96f-edf0-42c7-82e9-98249ee90c98)


Тепловая карта корреляции:
![image](https://github.com/user-attachments/assets/0088377c-5df3-4480-ac01-269b773cf2c2)
