# sorted-reverse
Sorted/reverse integers order of user's multiple inputs

# code

multiple_inputs=[int(nums) for nums in input("Enter multiple inputs: ").split()]
print(sorted(multiple_inputs))
ascending_nums=sorted(multiple_inputs)
descending_nums=ascending_nums[::-1]
print(descending_nums)
