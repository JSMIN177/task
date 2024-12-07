# task
git init
git add bit_manipulation.c
git commit -m "Initial commit: Add bit manipulation program"

bit_manipulation_project
touch bit_manipulation.c
}

// Function to set a bit
void setBit(unsigned int *number, int bitPosition) {
    *number |= (1 << bitPosition);
}
// Function to clear a bit
void clearBit(unsigned int *number, int bitPosition) {
    *number &= ~(1 << bitPosition);
}

// Function to toggle a bit
void toggleBit(unsigned int *number, int bitPosition) {
    *number ^= (1 << bitPosition);
}

// Function to read a bit
int readBit(unsigned int number, int bitPosition) {
    return (number >> bitPosition) & 1;
