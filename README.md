
# Solving problems with algorithms




## Problems

#### 1. Two Sum

```typescript
const twoSum = (numbers: number[], target: number): number[] => {
    const numbersLength = numbers?.length;
    
    for (let i = 0; i < numbersLength; i++) {
        
        for (let j = 0; j < numbersLength; j++) {

            if (i !== j)
                if (numbers[i] + numbers[j] === target) return [i, j]; 
        }
    }
};
```
