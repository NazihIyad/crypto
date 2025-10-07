#include <stdio.h>

int main() {
    char text[100];
    char mode;
    int i;

    printf("Enter mode (e=encrypt, d=decrypt): ");
    scanf(" %c", &mode);

    printf("Enter text (uppercase, no spaces): ");
    scanf("%s", text);

    for (i = 0; text[i] != '\0'; i++) {
        if (text[i] >= 'A' && text[i] <= 'Z') {
            if (mode == 'e') // encrypt
                text[i] = ((text[i] - 'A' + 3) % 26) + 'A';
            else // decrypt
                text[i] = ((text[i] - 'A' - 3 + 26) % 26) + 'A';
        }
    }

    printf("Result: %s\n", text);
    return 0;
}
