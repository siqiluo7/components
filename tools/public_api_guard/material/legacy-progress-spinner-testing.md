## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BaseHarnessFilters } from '@angular/cdk/testing';
import { ComponentHarness } from '@angular/cdk/testing';
import { HarnessPredicate } from '@angular/cdk/testing';
import { LegacyProgressSpinnerMode } from '@angular/material/legacy-progress-spinner';

// @public @deprecated
export interface LegacyProgressSpinnerHarnessFilters extends BaseHarnessFilters {
}

// @public @deprecated
export class MatLegacyProgressSpinnerHarness extends ComponentHarness {
    getMode(): Promise<LegacyProgressSpinnerMode>;
    getValue(): Promise<number | null>;
    static hostSelector: string;
    static with(options?: LegacyProgressSpinnerHarnessFilters): HarnessPredicate<MatLegacyProgressSpinnerHarness>;
}

// (No @packageDocumentation comment for this package)

```