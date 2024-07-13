<script>

  import * as Accordion from "$lib/components/ui/accordion";
</script>

<main class="bg-gray-900 text-white min-h-screen p-8">
  <h1 class="text-3xl font-bold mb-6">Frequently Asked Questions</h1>
  <Accordion.Root>
    <Accordion.Item value="item-1">
      <Accordion.Trigger class="text-xl font-semibold">What is AI code generation?</Accordion.Trigger>
      <Accordion.Content class="mt-2">
        AI code generation refers to the use of artificial intelligence to automatically generate code based on given inputs or requirements. This can help speed up development processes and reduce human error.
      </Accordion.Content>
    </Accordion.Item>
    <Accordion.Item value="item-2">
      <Accordion.Trigger class="text-xl font-semibold">How does AI code generation work?</Accordion.Trigger>
      <Accordion.Content class="mt-2">
        AI code generation typically involves training machine learning models on large datasets of code. These models learn patterns and best practices, which they then use to generate new code snippets or entire programs based on user inputs.
      </Accordion.Content>
    </Accordion.Item>
    <Accordion.Item value="item-3">
      <Accordion.Trigger class="text-xl font-semibold">What are the benefits of using AI for code generation?</Accordion.Trigger>
      <Accordion.Content class="mt-2">
        The benefits include increased development speed, reduced errors, and the ability to quickly prototype and iterate on ideas. It can also help developers learn new coding techniques and best practices.
      </Accordion.Content>
    </Accordion.Item>
    <Accordion.Item value="item-4">
      <Accordion.Trigger class="text-xl font-semibold">Are there any limitations to AI code generation?</Accordion.Trigger>
      <Accordion.Content class="mt-2">
        Yes, AI code generation is not perfect and can sometimes produce incorrect or suboptimal code. It is important for developers to review and test the generated code thoroughly. Additionally, AI models may not always understand the specific context or requirements of a project.
      </Accordion.Content>
    </Accordion.Item>
    <Accordion.Item value="item-5">
      <Accordion.Trigger class="text-xl font-semibold">Can AI replace human developers?</Accordion.Trigger>
      <Accordion.Content class="mt-2">
        While AI can assist in code generation and other development tasks, it is unlikely to completely replace human developers. Human creativity, problem-solving skills, and domain expertise are still essential for successful software development.
      </Accordion.Content>
    </Accordion.Item>
  </Accordion.Root>
</main>