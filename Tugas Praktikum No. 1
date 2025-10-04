#include <stdio.h>

int main() {
    int baris, kolom;
    int i, j;
    int pilihan;

    printf("Masukkan jumlah baris: ");
    scanf("%d", &baris);
    printf("Masukkan jumlah kolom: ");
    scanf("%d", &kolom);

    int A[10][10];
    int B[10][10];
    int hasil[10][10];

    printf("\nInput Matriks A:\n");
    for(i = 0; i < baris; i++) {
        for(j = 0; j < kolom; j++) {
            printf("A[%d][%d] = ", i, j);
            scanf("%d", &A[i][j]);
        }
    }

    printf("\nInput Matriks B:\n");
    for(i = 0; i < baris; i++) {
        for(j = 0; j < kolom; j++) {
            printf("B[%d][%d] = ", i, j);
            scanf("%d", &B[i][j]);
        }
    }

    printf("\nPilih operasi:\n");
    printf("1. Penjumlahan (A + B)\n");
    printf("2. Pengurangan (A - B)\n");
    printf("Masukkan pilihan (1 atau 2): ");
    scanf("%d", &pilihan);

    if(pilihan == 1) {
        for(i = 0; i < baris; i++) {
            for(j = 0; j < kolom; j++) {
                hasil[i][j] = A[i][j] + B[i][j];
            }
        }
        printf("\nHasil Penjumlahan (A + B):\n");
    } else if(pilihan == 2) {
        for(i = 0; i < baris; i++) {
            for(j = 0; j < kolom; j++) {
                hasil[i][j] = A[i][j] - B[i][j];
            }
        }
        printf("\nHasil Pengurangan (A - B):\n");
    } else {
        printf("Pilihan salah!\n");
        return 0;
    }

    printf("\nMatriks A:\n");
    for(i = 0; i < baris; i++) {
        for(j = 0; j < kolom; j++) {
            printf("%d ", A[i][j]);
        }
        printf("\n");
    }

    printf("\nMatriks B:\n");
    for(i = 0; i < baris; i++) {
        for(j = 0; j < kolom; j++) {
            printf("%d ", B[i][j]);
        }
        printf("\n");
    }

    printf("\nHasil:\n");
    for(i = 0; i < baris; i++) {
        for(j = 0; j < kolom; j++) {
            printf("%d ", hasil[i][j]);
        }
        printf("\n");
    }

    return 0;
}
