## API Report File for "angular-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public
export function formatRuntimeError<T = RuntimeErrorCode>(code: T, message: string): string;

// @public (undocumented)
export class RuntimeError<T = RuntimeErrorCode> extends Error {
    constructor(code: T, message: string);
    // (undocumented)
    code: T;
}

// @public
export const enum RuntimeErrorCode {
    // (undocumented)
    ALREADY_DESTROYED_PLATFORM = 404,
    // (undocumented)
    ASYNC_INITIALIZERS_STILL_RUNNING = 405,
    // (undocumented)
    BOOTSTRAP_COMPONENTS_NOT_FOUND = 403,
    // (undocumented)
    CYCLIC_DI_DEPENDENCY = -200,
    // (undocumented)
    ERROR_HANDLER_NOT_FOUND = 402,
    // (undocumented)
    EXPORT_NOT_FOUND = -301,
    // (undocumented)
    EXPRESSION_CHANGED_AFTER_CHECKED = -100,
    // (undocumented)
    MULTIPLE_COMPONENTS_MATCH = -300,
    // (undocumented)
    MULTIPLE_PLATFORMS = 400,
    // (undocumented)
    PIPE_NOT_FOUND = -302,
    // (undocumented)
    PLATFORM_NOT_FOUND = 401,
    // (undocumented)
    PROVIDER_NOT_FOUND = -201,
    // (undocumented)
    RECURSIVE_APPLICATION_REF_TICK = 101,
    // (undocumented)
    TEMPLATE_STRUCTURE_ERROR = 305,
    // (undocumented)
    UNKNOWN_BINDING = 303,
    // (undocumented)
    UNKNOWN_ELEMENT = 304
}

// (No @packageDocumentation comment for this package)

```
