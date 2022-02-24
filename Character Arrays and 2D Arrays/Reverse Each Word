void reverse(char input[], int i, int j){
    for(; i<=j; i++,j--){
        swap(input[i], input[j]);
    }
}

void reverseEachWord(char input[]) {
    // Write your code here
    for(int i=0,j=0; i<=strlen(input); i++){
        if(input[i] == ' ' || input[i] == '\0'){
            reverse(input, j, i-1);
            j = i + 1;
        }
    }
}
