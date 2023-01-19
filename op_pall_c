#include "monty.h"

/**
 * op_pall - print the value in the node
 * @stack: struct of doubly linked list
 * @line_number: number of the line in file
 */

void op_pall(stack_t **stack, unsigned int line_number)
{
	stack_t *tmp = *stack;
	(void) line_number;
	while (tmp != NULL)
	{
		printf("%d\n", tmp->n);
		tmp = tmp->next;
	}
}
