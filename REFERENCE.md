## Classes

<dl>
<dt><a href="#BaseAPI">BaseAPI</a></dt>
<dd></dd>
<dt><a href="#RequiredError">RequiredError</a> ⇐ <code>Error</code></dt>
<dd></dd>
<dt><a href="#AIApi">AIApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#AlertApi">AlertApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#DayApi">DayApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#DayContextApi">DayContextApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#DayTrendApi">DayTrendApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#ImportApi">ImportApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#ModelApi">ModelApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#PrevisionApi">PrevisionApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#SourceApi">SourceApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#SourceGroupApi">SourceGroupApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#UserApi">UserApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
<dt><a href="#ViewHelperApi">ViewHelperApi</a> ⇐ <code><a href="#BaseAPI">BaseAPI</a></code></dt>
<dd></dd>
</dl>

## Members

<dl>
<dt><a href="#COLLECTION_FORMATS">COLLECTION_FORMATS</a></dt>
<dd></dd>
</dl>

## Objects

<dl>
<dt><a href="#AlertDto">AlertDto</a> : <code>object</code></dt>
<dd></dd>
<dt><a href="#AlertRefDto">AlertRefDto</a> : <code>object</code></dt>
<dd></dd>
<dt><a href="#DayContext">DayContext</a> : <code>object</code></dt>
<dd></dd>
<dt><a href="#DayTrend">DayTrend</a> : <code>object</code></dt>
<dd></dd>
<dt><a href="#DayTrendInput">DayTrendInput</a> : <code>object</code></dt>
<dd></dd>
</dl>

## Functions

<dl>
<dt><a href="#AIApiFetchParamCreator">AIApiFetchParamCreator()</a></dt>
<dd><p>AIApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1AiAnomaliesSourceIdGet">v1AiAnomaliesSourceIdGet(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1AiRecomputeDayModelsSourceIdYearPost">v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>Erases and re-computes all day models for a source and year</p>
</dd>
<dt><a href="#v1AiRecomputeDaysProjectionSourceIdYearPost">v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>This computes the X/Y projection of all days in the source for the given year</p>
</dd>
<dt><a href="#v1AiRecomputeModelsSourceIdYearPost">v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])</a></dt>
<dd><p>This operations erases both non-handled alerts and user previsions</p>
</dd>
<dt><a href="#v1AiRecomputeSourceModelsModelCountPost">v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])</a></dt>
<dd><p>This operations erases the group configuration</p>
</dd>
<dt><a href="#AIApiFp">AIApiFp()</a></dt>
<dd><p>AIApi - functional programming interface</p>
</dd>
<dt><a href="#v1AiAnomaliesSourceIdGet">v1AiAnomaliesSourceIdGet(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1AiRecomputeDayModelsSourceIdYearPost">v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>Erases and re-computes all day models for a source and year</p>
</dd>
<dt><a href="#v1AiRecomputeDaysProjectionSourceIdYearPost">v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>This computes the X/Y projection of all days in the source for the given year</p>
</dd>
<dt><a href="#v1AiRecomputeModelsSourceIdYearPost">v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])</a></dt>
<dd><p>This operations erases both non-handled alerts and user previsions</p>
</dd>
<dt><a href="#v1AiRecomputeSourceModelsModelCountPost">v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])</a></dt>
<dd><p>This operations erases the group configuration</p>
</dd>
<dt><a href="#AIApiFactory">AIApiFactory()</a></dt>
<dd><p>AIApi - factory interface</p>
</dd>
<dt><a href="#v1AiAnomaliesSourceIdGet">v1AiAnomaliesSourceIdGet(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1AiRecomputeDayModelsSourceIdYearPost">v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>Erases and re-computes all day models for a source and year</p>
</dd>
<dt><a href="#v1AiRecomputeDaysProjectionSourceIdYearPost">v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>This computes the X/Y projection of all days in the source for the given year</p>
</dd>
<dt><a href="#v1AiRecomputeModelsSourceIdYearPost">v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])</a></dt>
<dd><p>This operations erases both non-handled alerts and user previsions</p>
</dd>
<dt><a href="#v1AiRecomputeSourceModelsModelCountPost">v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])</a></dt>
<dd><p>This operations erases the group configuration</p>
</dd>
<dt><a href="#AlertApiFetchParamCreator">AlertApiFetchParamCreator()</a></dt>
<dd><p>AlertApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1AlertAlertIdCommentPatch">v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])</a></dt>
<dd><p>A commented alert is closed and is moved to the alert referential</p>
</dd>
<dt><a href="#v1AlertAlertIdFavoritePatch">v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1AlertListGet">v1AlertListGet([sourceId], [year], [options])</a></dt>
<dd></dd>
<dt><a href="#v1AlertRefListGet">v1AlertRefListGet([sourceId], [year], [options])</a></dt>
<dd></dd>
<dt><a href="#AlertApiFp">AlertApiFp()</a></dt>
<dd><p>AlertApi - functional programming interface</p>
</dd>
<dt><a href="#v1AlertAlertIdCommentPatch">v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])</a></dt>
<dd><p>A commented alert is closed and is moved to the alert referential</p>
</dd>
<dt><a href="#v1AlertAlertIdFavoritePatch">v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1AlertListGet">v1AlertListGet([sourceId], [year], [options])</a></dt>
<dd></dd>
<dt><a href="#v1AlertRefListGet">v1AlertRefListGet([sourceId], [year], [options])</a></dt>
<dd></dd>
<dt><a href="#AlertApiFactory">AlertApiFactory()</a></dt>
<dd><p>AlertApi - factory interface</p>
</dd>
<dt><a href="#v1AlertAlertIdCommentPatch">v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])</a></dt>
<dd><p>A commented alert is closed and is moved to the alert referential</p>
</dd>
<dt><a href="#v1AlertAlertIdFavoritePatch">v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1AlertListGet">v1AlertListGet([sourceId], [year], [options])</a></dt>
<dd></dd>
<dt><a href="#v1AlertRefListGet">v1AlertRefListGet([sourceId], [year], [options])</a></dt>
<dd></dd>
<dt><a href="#DayApiFetchParamCreator">DayApiFetchParamCreator()</a></dt>
<dd><p>DayApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1DayBulkPatch">v1DayBulkPatch(DaysPatchDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayListSourceIdYearGet">v1DayListSourceIdYearGet(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#DayApiFp">DayApiFp()</a></dt>
<dd><p>DayApi - functional programming interface</p>
</dd>
<dt><a href="#v1DayBulkPatch">v1DayBulkPatch(DaysPatchDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayListSourceIdYearGet">v1DayListSourceIdYearGet(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#DayApiFactory">DayApiFactory()</a></dt>
<dd><p>DayApi - factory interface</p>
</dd>
<dt><a href="#v1DayBulkPatch">v1DayBulkPatch(DaysPatchDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayListSourceIdYearGet">v1DayListSourceIdYearGet(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#DayContextApiFetchParamCreator">DayContextApiFetchParamCreator()</a></dt>
<dd><p>DayContextApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1DayContextBulkPost">v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextGet">v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdDelete">v1DayContextIdDelete(id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdGet">v1DayContextIdGet(id, [fields], [join], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdPatch">v1DayContextIdPatch(DayContext, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdPut">v1DayContextIdPut(DayContext, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextImportMeteoCsvSourceIdPost">v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextPost">v1DayContextPost(DayContext, [options])</a></dt>
<dd></dd>
<dt><a href="#DayContextApiFp">DayContextApiFp()</a></dt>
<dd><p>DayContextApi - functional programming interface</p>
</dd>
<dt><a href="#v1DayContextBulkPost">v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextGet">v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdDelete">v1DayContextIdDelete(id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdGet">v1DayContextIdGet(id, [fields], [join], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdPatch">v1DayContextIdPatch(DayContext, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdPut">v1DayContextIdPut(DayContext, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextImportMeteoCsvSourceIdPost">v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextPost">v1DayContextPost(DayContext, [options])</a></dt>
<dd></dd>
<dt><a href="#DayContextApiFactory">DayContextApiFactory()</a></dt>
<dd><p>DayContextApi - factory interface</p>
</dd>
<dt><a href="#v1DayContextBulkPost">v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextGet">v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdDelete">v1DayContextIdDelete(id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdGet">v1DayContextIdGet(id, [fields], [join], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdPatch">v1DayContextIdPatch(DayContext, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextIdPut">v1DayContextIdPut(DayContext, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextImportMeteoCsvSourceIdPost">v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayContextPost">v1DayContextPost(DayContext, [options])</a></dt>
<dd></dd>
<dt><a href="#DayTrendApiFetchParamCreator">DayTrendApiFetchParamCreator()</a></dt>
<dd><p>DayTrendApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1DayTrendBulkPost">v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendGet">v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdDelete">v1DayTrendIdDelete(id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdGet">v1DayTrendIdGet(id, [fields], [join], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdPatch">v1DayTrendIdPatch(DayTrend, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdPut">v1DayTrendIdPut(DayTrend, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendPost">v1DayTrendPost(DayTrend, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendReplaceAllInSourceSourceIdPost">v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])</a></dt>
<dd></dd>
<dt><a href="#DayTrendApiFp">DayTrendApiFp()</a></dt>
<dd><p>DayTrendApi - functional programming interface</p>
</dd>
<dt><a href="#v1DayTrendBulkPost">v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendGet">v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdDelete">v1DayTrendIdDelete(id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdGet">v1DayTrendIdGet(id, [fields], [join], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdPatch">v1DayTrendIdPatch(DayTrend, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdPut">v1DayTrendIdPut(DayTrend, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendPost">v1DayTrendPost(DayTrend, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendReplaceAllInSourceSourceIdPost">v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])</a></dt>
<dd></dd>
<dt><a href="#DayTrendApiFactory">DayTrendApiFactory()</a></dt>
<dd><p>DayTrendApi - factory interface</p>
</dd>
<dt><a href="#v1DayTrendBulkPost">v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendGet">v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdDelete">v1DayTrendIdDelete(id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdGet">v1DayTrendIdGet(id, [fields], [join], [cache], [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdPatch">v1DayTrendIdPatch(DayTrend, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendIdPut">v1DayTrendIdPut(DayTrend, id, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendPost">v1DayTrendPost(DayTrend, [options])</a></dt>
<dd></dd>
<dt><a href="#v1DayTrendReplaceAllInSourceSourceIdPost">v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])</a></dt>
<dd></dd>
<dt><a href="#ImportApiFetchParamCreator">ImportApiFetchParamCreator()</a></dt>
<dd><p>ImportApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1ImportCreateSourcePost">v1ImportCreateSourcePost(CreateSourceDto, [options])</a></dt>
<dd><p>Creates a source, add a first batch of day data, then computes the models for the first time.</p>
</dd>
<dt><a href="#v1ImportDaysPost">v1ImportDaysPost(ImportDaysDto, [options])</a></dt>
<dd><p>When new data is added, we compute alerts for this data</p>
</dd>
<dt><a href="#v1ImportReprocessDaysSourceIdYearPost">v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>Compute maps, alerts and closest models</p>
</dd>
<dt><a href="#v1ImportSourceIdDaysPost">v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])</a></dt>
<dd><p>When new data is added, we compute alerts for this data</p>
</dd>
<dt><a href="#ImportApiFp">ImportApiFp()</a></dt>
<dd><p>ImportApi - functional programming interface</p>
</dd>
<dt><a href="#v1ImportCreateSourcePost">v1ImportCreateSourcePost(CreateSourceDto, [options])</a></dt>
<dd><p>Creates a source, add a first batch of day data, then computes the models for the first time.</p>
</dd>
<dt><a href="#v1ImportDaysPost">v1ImportDaysPost(ImportDaysDto, [options])</a></dt>
<dd><p>When new data is added, we compute alerts for this data</p>
</dd>
<dt><a href="#v1ImportReprocessDaysSourceIdYearPost">v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>Compute maps, alerts and closest models</p>
</dd>
<dt><a href="#v1ImportSourceIdDaysPost">v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])</a></dt>
<dd><p>When new data is added, we compute alerts for this data</p>
</dd>
<dt><a href="#ImportApiFactory">ImportApiFactory()</a></dt>
<dd><p>ImportApi - factory interface</p>
</dd>
<dt><a href="#v1ImportCreateSourcePost">v1ImportCreateSourcePost(CreateSourceDto, [options])</a></dt>
<dd><p>Creates a source, add a first batch of day data, then computes the models for the first time.</p>
</dd>
<dt><a href="#v1ImportDaysPost">v1ImportDaysPost(ImportDaysDto, [options])</a></dt>
<dd><p>When new data is added, we compute alerts for this data</p>
</dd>
<dt><a href="#v1ImportReprocessDaysSourceIdYearPost">v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd><p>Compute maps, alerts and closest models</p>
</dd>
<dt><a href="#v1ImportSourceIdDaysPost">v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])</a></dt>
<dd><p>When new data is added, we compute alerts for this data</p>
</dd>
<dt><a href="#ModelApiFetchParamCreator">ModelApiFetchParamCreator()</a></dt>
<dd><p>ModelApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1ModelBulkPatch">v1ModelBulkPatch(ModelsPatchDto, [options])</a></dt>
<dd><p>Update many models at once, mainly used to set color and name of the model</p>
</dd>
<dt><a href="#v1ModelListSourceIdGet">v1ModelListSourceIdGet(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#ModelApiFp">ModelApiFp()</a></dt>
<dd><p>ModelApi - functional programming interface</p>
</dd>
<dt><a href="#v1ModelBulkPatch">v1ModelBulkPatch(ModelsPatchDto, [options])</a></dt>
<dd><p>Update many models at once, mainly used to set color and name of the model</p>
</dd>
<dt><a href="#v1ModelListSourceIdGet">v1ModelListSourceIdGet(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#ModelApiFactory">ModelApiFactory()</a></dt>
<dd><p>ModelApi - factory interface</p>
</dd>
<dt><a href="#v1ModelBulkPatch">v1ModelBulkPatch(ModelsPatchDto, [options])</a></dt>
<dd><p>Update many models at once, mainly used to set color and name of the model</p>
</dd>
<dt><a href="#v1ModelListSourceIdGet">v1ModelListSourceIdGet(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#PrevisionApiFetchParamCreator">PrevisionApiFetchParamCreator()</a></dt>
<dd><p>PrevisionApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1PrevisionGroupApplyPrevisionPost">v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionListSourceIdYearGet">v1PrevisionListSourceIdYearGet(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionSaveDefaultPrevisionsSourceIdYearPost">v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionSavePost">v1PrevisionSavePost(PrevisionBulkSaveDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionUpdatePatch">v1PrevisionUpdatePatch(PrevisionPatchDto, [options])</a></dt>
<dd></dd>
<dt><a href="#PrevisionApiFp">PrevisionApiFp()</a></dt>
<dd><p>PrevisionApi - functional programming interface</p>
</dd>
<dt><a href="#v1PrevisionGroupApplyPrevisionPost">v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionListSourceIdYearGet">v1PrevisionListSourceIdYearGet(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionSaveDefaultPrevisionsSourceIdYearPost">v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionSavePost">v1PrevisionSavePost(PrevisionBulkSaveDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionUpdatePatch">v1PrevisionUpdatePatch(PrevisionPatchDto, [options])</a></dt>
<dd></dd>
<dt><a href="#PrevisionApiFactory">PrevisionApiFactory()</a></dt>
<dd><p>PrevisionApi - factory interface</p>
</dd>
<dt><a href="#v1PrevisionGroupApplyPrevisionPost">v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionListSourceIdYearGet">v1PrevisionListSourceIdYearGet(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionSaveDefaultPrevisionsSourceIdYearPost">v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionSavePost">v1PrevisionSavePost(PrevisionBulkSaveDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1PrevisionUpdatePatch">v1PrevisionUpdatePatch(PrevisionPatchDto, [options])</a></dt>
<dd></dd>
<dt><a href="#SourceApiFetchParamCreator">SourceApiFetchParamCreator()</a></dt>
<dd><p>SourceApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1SourceListGet">v1SourceListGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdDelete">v1SourceSourceIdDelete(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdGroupPatch">v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdPatch">v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#SourceApiFp">SourceApiFp()</a></dt>
<dd><p>SourceApi - functional programming interface</p>
</dd>
<dt><a href="#v1SourceListGet">v1SourceListGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdDelete">v1SourceSourceIdDelete(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdGroupPatch">v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdPatch">v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#SourceApiFactory">SourceApiFactory()</a></dt>
<dd><p>SourceApi - factory interface</p>
</dd>
<dt><a href="#v1SourceListGet">v1SourceListGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdDelete">v1SourceSourceIdDelete(sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdGroupPatch">v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceSourceIdPatch">v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#SourceGroupApiFetchParamCreator">SourceGroupApiFetchParamCreator()</a></dt>
<dd><p>SourceGroupApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1SourceGroupCreatePost">v1SourceGroupCreatePost(SourceGroupCreateDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceGroupGroupIdPatch">v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceGroupListGet">v1SourceGroupListGet([options])</a></dt>
<dd></dd>
<dt><a href="#SourceGroupApiFp">SourceGroupApiFp()</a></dt>
<dd><p>SourceGroupApi - functional programming interface</p>
</dd>
<dt><a href="#v1SourceGroupCreatePost">v1SourceGroupCreatePost(SourceGroupCreateDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceGroupGroupIdPatch">v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceGroupListGet">v1SourceGroupListGet([options])</a></dt>
<dd></dd>
<dt><a href="#SourceGroupApiFactory">SourceGroupApiFactory()</a></dt>
<dd><p>SourceGroupApi - factory interface</p>
</dd>
<dt><a href="#v1SourceGroupCreatePost">v1SourceGroupCreatePost(SourceGroupCreateDto, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceGroupGroupIdPatch">v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])</a></dt>
<dd></dd>
<dt><a href="#v1SourceGroupListGet">v1SourceGroupListGet([options])</a></dt>
<dd></dd>
<dt><a href="#UserApiFetchParamCreator">UserApiFetchParamCreator()</a></dt>
<dd><p>UserApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1UserLoginPost">v1UserLoginPost(LoginDto, [options])</a></dt>
<dd><p>This endpoints returns the jwt and sets a cookie with the same jwt.      This way you can use it from both an api and a browser</p>
</dd>
<dt><a href="#v1UserMeGet">v1UserMeGet([options])</a></dt>
<dd><p>Must be authenticated to call this endpoint</p>
</dd>
<dt><a href="#v1UserRegisterDemoPost">v1UserRegisterDemoPost(RequestDemoDto, [options])</a></dt>
<dd></dd>
<dt><a href="#UserApiFp">UserApiFp()</a></dt>
<dd><p>UserApi - functional programming interface</p>
</dd>
<dt><a href="#v1UserLoginPost">v1UserLoginPost(LoginDto, [options])</a></dt>
<dd><p>This endpoints returns the jwt and sets a cookie with the same jwt.      This way you can use it from both an api and a browser</p>
</dd>
<dt><a href="#v1UserMeGet">v1UserMeGet([options])</a></dt>
<dd><p>Must be authenticated to call this endpoint</p>
</dd>
<dt><a href="#v1UserRegisterDemoPost">v1UserRegisterDemoPost(RequestDemoDto, [options])</a></dt>
<dd></dd>
<dt><a href="#UserApiFactory">UserApiFactory()</a></dt>
<dd><p>UserApi - factory interface</p>
</dd>
<dt><a href="#v1UserLoginPost">v1UserLoginPost(LoginDto, [options])</a></dt>
<dd><p>This endpoints returns the jwt and sets a cookie with the same jwt.      This way you can use it from both an api and a browser</p>
</dd>
<dt><a href="#v1UserMeGet">v1UserMeGet([options])</a></dt>
<dd><p>Must be authenticated to call this endpoint</p>
</dd>
<dt><a href="#v1UserRegisterDemoPost">v1UserRegisterDemoPost(RequestDemoDto, [options])</a></dt>
<dd></dd>
<dt><a href="#ViewHelperApiFetchParamCreator">ViewHelperApiFetchParamCreator()</a></dt>
<dd><p>ViewHelperApi - fetch parameter creator</p>
</dd>
<dt><a href="#v1ViewHelperAlertsGet">v1ViewHelperAlertsGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1ViewHelperAlertsRefGet">v1ViewHelperAlertsRefGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1ViewHelperDaysNearDateSourceIdDayDateGet">v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#ViewHelperApiFp">ViewHelperApiFp()</a></dt>
<dd><p>ViewHelperApi - functional programming interface</p>
</dd>
<dt><a href="#v1ViewHelperAlertsGet">v1ViewHelperAlertsGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1ViewHelperAlertsRefGet">v1ViewHelperAlertsRefGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1ViewHelperDaysNearDateSourceIdDayDateGet">v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])</a></dt>
<dd></dd>
<dt><a href="#ViewHelperApiFactory">ViewHelperApiFactory()</a></dt>
<dd><p>ViewHelperApi - factory interface</p>
</dd>
<dt><a href="#v1ViewHelperAlertsGet">v1ViewHelperAlertsGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1ViewHelperAlertsRefGet">v1ViewHelperAlertsRefGet([options])</a></dt>
<dd></dd>
<dt><a href="#v1ViewHelperDaysNearDateSourceIdDayDateGet">v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])</a></dt>
<dd></dd>
</dl>

<a name="BaseAPI"></a>

## BaseAPI
**Kind**: global class  
<a name="RequiredError"></a>

## RequiredError ⇐ <code>Error</code>
**Kind**: global class  
**Extends**: <code>Error</code>  
<a name="AIApi"></a>

## AIApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [AIApi](#AIApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new AIApi()](#new_AIApi_new)
    * [.v1AiAnomaliesSourceIdGet(sourceId, [options])](#AIApi+v1AiAnomaliesSourceIdGet)
    * [.v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])](#AIApi+v1AiRecomputeDayModelsSourceIdYearPost)
    * [.v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])](#AIApi+v1AiRecomputeDaysProjectionSourceIdYearPost)
    * [.v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])](#AIApi+v1AiRecomputeModelsSourceIdYearPost)
    * [.v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])](#AIApi+v1AiRecomputeSourceModelsModelCountPost)

<a name="new_AIApi_new"></a>

### new AIApi()
AIApi - object-oriented interface

<a name="AIApi+v1AiAnomaliesSourceIdGet"></a>

### aiApi.v1AiAnomaliesSourceIdGet(sourceId, [options])
**Kind**: instance method of [<code>AIApi</code>](#AIApi)  
**Summary**: Auto detect-anomalies  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AIApi+v1AiRecomputeDayModelsSourceIdYearPost"></a>

### aiApi.v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])
Erases and re-computes all day models for a source and year

**Kind**: instance method of [<code>AIApi</code>](#AIApi)  
**Summary**: Recomputes all day modesl  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AIApi+v1AiRecomputeDaysProjectionSourceIdYearPost"></a>

### aiApi.v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])
This computes the X/Y projection of all days in the source for the given year

**Kind**: instance method of [<code>AIApi</code>](#AIApi)  
**Summary**: Computes all days projection for a source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AIApi+v1AiRecomputeModelsSourceIdYearPost"></a>

### aiApi.v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])
This operations erases both non-handled alerts and user previsions

**Kind**: instance method of [<code>AIApi</code>](#AIApi)  
**Summary**: Triggers a model recompute  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [modelCount] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AIApi+v1AiRecomputeSourceModelsModelCountPost"></a>

### aiApi.v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])
This operations erases the group configuration

**Kind**: instance method of [<code>AIApi</code>](#AIApi)  
**Summary**: Triggers a model recompute for source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| modelCount | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AlertApi"></a>

## AlertApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [AlertApi](#AlertApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new AlertApi()](#new_AlertApi_new)
    * [.v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])](#AlertApi+v1AlertAlertIdCommentPatch)
    * [.v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])](#AlertApi+v1AlertAlertIdFavoritePatch)
    * [.v1AlertListGet([sourceId], [year], [options])](#AlertApi+v1AlertListGet)
    * [.v1AlertRefListGet([sourceId], [year], [options])](#AlertApi+v1AlertRefListGet)

<a name="new_AlertApi_new"></a>

### new AlertApi()
AlertApi - object-oriented interface

<a name="AlertApi+v1AlertAlertIdCommentPatch"></a>

### alertApi.v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])
A commented alert is closed and is moved to the alert referential

**Kind**: instance method of [<code>AlertApi</code>](#AlertApi)  
**Summary**: Add a comment to an alert  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertCommentDto | <code>AlertCommentDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AlertApi+v1AlertAlertIdFavoritePatch"></a>

### alertApi.v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])
**Kind**: instance method of [<code>AlertApi</code>](#AlertApi)  
**Summary**: Set alert favorite for the current user  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertFavoriteDto | <code>AlertFavoriteDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AlertApi+v1AlertListGet"></a>

### alertApi.v1AlertListGet([sourceId], [year], [options])
**Kind**: instance method of [<code>AlertApi</code>](#AlertApi)  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AlertApi+v1AlertRefListGet"></a>

### alertApi.v1AlertRefListGet([sourceId], [year], [options])
**Kind**: instance method of [<code>AlertApi</code>](#AlertApi)  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayApi"></a>

## DayApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [DayApi](#DayApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new DayApi()](#new_DayApi_new)
    * [.v1DayBulkPatch(DaysPatchDto, [options])](#DayApi+v1DayBulkPatch)
    * [.v1DayListSourceIdYearGet(year, sourceId, [options])](#DayApi+v1DayListSourceIdYearGet)

<a name="new_DayApi_new"></a>

### new DayApi()
DayApi - object-oriented interface

<a name="DayApi+v1DayBulkPatch"></a>

### dayApi.v1DayBulkPatch(DaysPatchDto, [options])
**Kind**: instance method of [<code>DayApi</code>](#DayApi)  
**Summary**: Update day entities  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DaysPatchDto | <code>DaysPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayApi+v1DayListSourceIdYearGet"></a>

### dayApi.v1DayListSourceIdYearGet(year, sourceId, [options])
**Kind**: instance method of [<code>DayApi</code>](#DayApi)  
**Summary**: List day data of the reference year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi"></a>

## DayContextApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [DayContextApi](#DayContextApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new DayContextApi()](#new_DayContextApi_new)
    * [.v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])](#DayContextApi+v1DayContextBulkPost)
    * [.v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])](#DayContextApi+v1DayContextGet)
    * [.v1DayContextIdDelete(id, [options])](#DayContextApi+v1DayContextIdDelete)
    * [.v1DayContextIdGet(id, [fields], [join], [cache], [options])](#DayContextApi+v1DayContextIdGet)
    * [.v1DayContextIdPatch(DayContext, id, [options])](#DayContextApi+v1DayContextIdPatch)
    * [.v1DayContextIdPut(DayContext, id, [options])](#DayContextApi+v1DayContextIdPut)
    * [.v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])](#DayContextApi+v1DayContextImportMeteoCsvSourceIdPost)
    * [.v1DayContextPost(DayContext, [options])](#DayContextApi+v1DayContextPost)

<a name="new_DayContextApi_new"></a>

### new DayContextApi()
DayContextApi - object-oriented interface

<a name="DayContextApi+v1DayContextBulkPost"></a>

### dayContextApi.v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Create many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayContextBulkDto | <code>GeneratedDayContextBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi+v1DayContextGet"></a>

### dayContextApi.v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Retrieve many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi+v1DayContextIdDelete"></a>

### dayContextApi.v1DayContextIdDelete(id, [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Delete one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi+v1DayContextIdGet"></a>

### dayContextApi.v1DayContextIdGet(id, [fields], [join], [cache], [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Retrieve one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi+v1DayContextIdPatch"></a>

### dayContextApi.v1DayContextIdPatch(DayContext, id, [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Update one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi+v1DayContextIdPut"></a>

### dayContextApi.v1DayContextIdPut(DayContext, id, [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Replace one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi+v1DayContextImportMeteoCsvSourceIdPost"></a>

### dayContextApi.v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Imports a meteo csv file for the source id  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApi+v1DayContextPost"></a>

### dayContextApi.v1DayContextPost(DayContext, [options])
**Kind**: instance method of [<code>DayContextApi</code>](#DayContextApi)  
**Summary**: Create one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi"></a>

## DayTrendApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [DayTrendApi](#DayTrendApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new DayTrendApi()](#new_DayTrendApi_new)
    * [.v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])](#DayTrendApi+v1DayTrendBulkPost)
    * [.v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])](#DayTrendApi+v1DayTrendGet)
    * [.v1DayTrendIdDelete(id, [options])](#DayTrendApi+v1DayTrendIdDelete)
    * [.v1DayTrendIdGet(id, [fields], [join], [cache], [options])](#DayTrendApi+v1DayTrendIdGet)
    * [.v1DayTrendIdPatch(DayTrend, id, [options])](#DayTrendApi+v1DayTrendIdPatch)
    * [.v1DayTrendIdPut(DayTrend, id, [options])](#DayTrendApi+v1DayTrendIdPut)
    * [.v1DayTrendPost(DayTrend, [options])](#DayTrendApi+v1DayTrendPost)
    * [.v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])](#DayTrendApi+v1DayTrendReplaceAllInSourceSourceIdPost)

<a name="new_DayTrendApi_new"></a>

### new DayTrendApi()
DayTrendApi - object-oriented interface

<a name="DayTrendApi+v1DayTrendBulkPost"></a>

### dayTrendApi.v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Create many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayTrendBulkDto | <code>GeneratedDayTrendBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi+v1DayTrendGet"></a>

### dayTrendApi.v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Retrieve many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi+v1DayTrendIdDelete"></a>

### dayTrendApi.v1DayTrendIdDelete(id, [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Delete one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi+v1DayTrendIdGet"></a>

### dayTrendApi.v1DayTrendIdGet(id, [fields], [join], [cache], [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Retrieve one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi+v1DayTrendIdPatch"></a>

### dayTrendApi.v1DayTrendIdPatch(DayTrend, id, [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Update one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi+v1DayTrendIdPut"></a>

### dayTrendApi.v1DayTrendIdPut(DayTrend, id, [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Replace one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi+v1DayTrendPost"></a>

### dayTrendApi.v1DayTrendPost(DayTrend, [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Create one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApi+v1DayTrendReplaceAllInSourceSourceIdPost"></a>

### dayTrendApi.v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])
**Kind**: instance method of [<code>DayTrendApi</code>](#DayTrendApi)  
**Summary**: Imports many trends and replace existing. Recomputes alerts  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| DayTrendInputListDto | <code>DayTrendInputListDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ImportApi"></a>

## ImportApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [ImportApi](#ImportApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new ImportApi()](#new_ImportApi_new)
    * [.v1ImportCreateSourcePost(CreateSourceDto, [options])](#ImportApi+v1ImportCreateSourcePost)
    * [.v1ImportDaysPost(ImportDaysDto, [options])](#ImportApi+v1ImportDaysPost)
    * [.v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])](#ImportApi+v1ImportReprocessDaysSourceIdYearPost)
    * [.v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])](#ImportApi+v1ImportSourceIdDaysPost)

<a name="new_ImportApi_new"></a>

### new ImportApi()
ImportApi - object-oriented interface

<a name="ImportApi+v1ImportCreateSourcePost"></a>

### importApi.v1ImportCreateSourcePost(CreateSourceDto, [options])
Creates a source, add a first batch of day data, then computes the models for the first time.

**Kind**: instance method of [<code>ImportApi</code>](#ImportApi)  
**Summary**: First source creation  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| CreateSourceDto | <code>CreateSourceDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ImportApi+v1ImportDaysPost"></a>

### importApi.v1ImportDaysPost(ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: instance method of [<code>ImportApi</code>](#ImportApi)  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ImportApi+v1ImportReprocessDaysSourceIdYearPost"></a>

### importApi.v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])
Compute maps, alerts and closest models

**Kind**: instance method of [<code>ImportApi</code>](#ImportApi)  
**Summary**: Reprocess days from database  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ImportApi+v1ImportSourceIdDaysPost"></a>

### importApi.v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: instance method of [<code>ImportApi</code>](#ImportApi)  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ModelApi"></a>

## ModelApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [ModelApi](#ModelApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new ModelApi()](#new_ModelApi_new)
    * [.v1ModelBulkPatch(ModelsPatchDto, [options])](#ModelApi+v1ModelBulkPatch)
    * [.v1ModelListSourceIdGet(sourceId, [options])](#ModelApi+v1ModelListSourceIdGet)

<a name="new_ModelApi_new"></a>

### new ModelApi()
ModelApi - object-oriented interface

<a name="ModelApi+v1ModelBulkPatch"></a>

### modelApi.v1ModelBulkPatch(ModelsPatchDto, [options])
Update many models at once, mainly used to set color and name of the model

**Kind**: instance method of [<code>ModelApi</code>](#ModelApi)  
**Summary**: Model bulk update  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ModelsPatchDto | <code>ModelsPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ModelApi+v1ModelListSourceIdGet"></a>

### modelApi.v1ModelListSourceIdGet(sourceId, [options])
**Kind**: instance method of [<code>ModelApi</code>](#ModelApi)  
**Summary**: List models data of this source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApi"></a>

## PrevisionApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [PrevisionApi](#PrevisionApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new PrevisionApi()](#new_PrevisionApi_new)
    * [.v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])](#PrevisionApi+v1PrevisionGroupApplyPrevisionPost)
    * [.v1PrevisionListSourceIdYearGet(year, sourceId, [options])](#PrevisionApi+v1PrevisionListSourceIdYearGet)
    * [.v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])](#PrevisionApi+v1PrevisionSaveDefaultPrevisionsSourceIdYearPost)
    * [.v1PrevisionSavePost(PrevisionBulkSaveDto, [options])](#PrevisionApi+v1PrevisionSavePost)
    * [.v1PrevisionUpdatePatch(PrevisionPatchDto, [options])](#PrevisionApi+v1PrevisionUpdatePatch)

<a name="new_PrevisionApi_new"></a>

### new PrevisionApi()
PrevisionApi - object-oriented interface

<a name="PrevisionApi+v1PrevisionGroupApplyPrevisionPost"></a>

### previsionApi.v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])
**Kind**: instance method of [<code>PrevisionApi</code>](#PrevisionApi)  
**Summary**: Apply a source prevision to the whole group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionApplyGroupDto | <code>PrevisionApplyGroupDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApi+v1PrevisionListSourceIdYearGet"></a>

### previsionApi.v1PrevisionListSourceIdYearGet(year, sourceId, [options])
**Kind**: instance method of [<code>PrevisionApi</code>](#PrevisionApi)  
**Summary**: Fetch data previsions for a given year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApi+v1PrevisionSaveDefaultPrevisionsSourceIdYearPost"></a>

### previsionApi.v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])
**Kind**: instance method of [<code>PrevisionApi</code>](#PrevisionApi)  
**Summary**: Generate default previsions for the source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApi+v1PrevisionSavePost"></a>

### previsionApi.v1PrevisionSavePost(PrevisionBulkSaveDto, [options])
**Kind**: instance method of [<code>PrevisionApi</code>](#PrevisionApi)  
**Summary**: Save many previsions at once  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionBulkSaveDto | <code>PrevisionBulkSaveDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApi+v1PrevisionUpdatePatch"></a>

### previsionApi.v1PrevisionUpdatePatch(PrevisionPatchDto, [options])
**Kind**: instance method of [<code>PrevisionApi</code>](#PrevisionApi)  
**Summary**: Update a specific prevision  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionPatchDto | <code>PrevisionPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceApi"></a>

## SourceApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [SourceApi](#SourceApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new SourceApi()](#new_SourceApi_new)
    * [.v1SourceListGet([options])](#SourceApi+v1SourceListGet)
    * [.v1SourceSourceIdDelete(sourceId, [options])](#SourceApi+v1SourceSourceIdDelete)
    * [.v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])](#SourceApi+v1SourceSourceIdGroupPatch)
    * [.v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])](#SourceApi+v1SourceSourceIdPatch)

<a name="new_SourceApi_new"></a>

### new SourceApi()
SourceApi - object-oriented interface

<a name="SourceApi+v1SourceListGet"></a>

### sourceApi.v1SourceListGet([options])
**Kind**: instance method of [<code>SourceApi</code>](#SourceApi)  
**Summary**: All user sources  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceApi+v1SourceSourceIdDelete"></a>

### sourceApi.v1SourceSourceIdDelete(sourceId, [options])
**Kind**: instance method of [<code>SourceApi</code>](#SourceApi)  
**Summary**: Delete a source and all linked data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceApi+v1SourceSourceIdGroupPatch"></a>

### sourceApi.v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])
**Kind**: instance method of [<code>SourceApi</code>](#SourceApi)  
**Summary**: Update a source group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchGroupDto | <code>SourcePatchGroupDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceApi+v1SourceSourceIdPatch"></a>

### sourceApi.v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])
**Kind**: instance method of [<code>SourceApi</code>](#SourceApi)  
**Summary**: Update a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchDto | <code>SourcePatchDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceGroupApi"></a>

## SourceGroupApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [SourceGroupApi](#SourceGroupApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new SourceGroupApi()](#new_SourceGroupApi_new)
    * [.v1SourceGroupCreatePost(SourceGroupCreateDto, [options])](#SourceGroupApi+v1SourceGroupCreatePost)
    * [.v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])](#SourceGroupApi+v1SourceGroupGroupIdPatch)
    * [.v1SourceGroupListGet([options])](#SourceGroupApi+v1SourceGroupListGet)

<a name="new_SourceGroupApi_new"></a>

### new SourceGroupApi()
SourceGroupApi - object-oriented interface

<a name="SourceGroupApi+v1SourceGroupCreatePost"></a>

### sourceGroupApi.v1SourceGroupCreatePost(SourceGroupCreateDto, [options])
**Kind**: instance method of [<code>SourceGroupApi</code>](#SourceGroupApi)  
**Summary**: Create a new source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupCreateDto | <code>SourceGroupCreateDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceGroupApi+v1SourceGroupGroupIdPatch"></a>

### sourceGroupApi.v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])
**Kind**: instance method of [<code>SourceGroupApi</code>](#SourceGroupApi)  
**Summary**: Updates a group configuration  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupPatchDto | <code>SourceGroupPatchDto</code> |  |
| groupId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceGroupApi+v1SourceGroupListGet"></a>

### sourceGroupApi.v1SourceGroupListGet([options])
**Kind**: instance method of [<code>SourceGroupApi</code>](#SourceGroupApi)  
**Summary**: All source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="UserApi"></a>

## UserApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [UserApi](#UserApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new UserApi()](#new_UserApi_new)
    * [.v1UserLoginPost(LoginDto, [options])](#UserApi+v1UserLoginPost)
    * [.v1UserMeGet([options])](#UserApi+v1UserMeGet)
    * [.v1UserRegisterDemoPost(RequestDemoDto, [options])](#UserApi+v1UserRegisterDemoPost)

<a name="new_UserApi_new"></a>

### new UserApi()
UserApi - object-oriented interface

<a name="UserApi+v1UserLoginPost"></a>

### userApi.v1UserLoginPost(LoginDto, [options])
This endpoints returns the jwt and sets a cookie with the same jwt.      This way you can use it from both an api and a browser

**Kind**: instance method of [<code>UserApi</code>](#UserApi)  
**Summary**: Log the user in  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| LoginDto | <code>LoginDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="UserApi+v1UserMeGet"></a>

### userApi.v1UserMeGet([options])
Must be authenticated to call this endpoint

**Kind**: instance method of [<code>UserApi</code>](#UserApi)  
**Summary**: Retrieve current user information  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="UserApi+v1UserRegisterDemoPost"></a>

### userApi.v1UserRegisterDemoPost(RequestDemoDto, [options])
**Kind**: instance method of [<code>UserApi</code>](#UserApi)  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| RequestDemoDto | <code>RequestDemoDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ViewHelperApi"></a>

## ViewHelperApi ⇐ [<code>BaseAPI</code>](#BaseAPI)
**Kind**: global class  
**Extends**: [<code>BaseAPI</code>](#BaseAPI)  

* [ViewHelperApi](#ViewHelperApi) ⇐ [<code>BaseAPI</code>](#BaseAPI)
    * [new ViewHelperApi()](#new_ViewHelperApi_new)
    * [.v1ViewHelperAlertsGet([options])](#ViewHelperApi+v1ViewHelperAlertsGet)
    * [.v1ViewHelperAlertsRefGet([options])](#ViewHelperApi+v1ViewHelperAlertsRefGet)
    * [.v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])](#ViewHelperApi+v1ViewHelperDaysNearDateSourceIdDayDateGet)

<a name="new_ViewHelperApi_new"></a>

### new ViewHelperApi()
ViewHelperApi - object-oriented interface

<a name="ViewHelperApi+v1ViewHelperAlertsGet"></a>

### viewHelperApi.v1ViewHelperAlertsGet([options])
**Kind**: instance method of [<code>ViewHelperApi</code>](#ViewHelperApi)  
**Summary**: Get the alert view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="ViewHelperApi+v1ViewHelperAlertsRefGet"></a>

### viewHelperApi.v1ViewHelperAlertsRefGet([options])
**Kind**: instance method of [<code>ViewHelperApi</code>](#ViewHelperApi)  
**Summary**: Get the alert referential view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="ViewHelperApi+v1ViewHelperDaysNearDateSourceIdDayDateGet"></a>

### viewHelperApi.v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])
**Kind**: instance method of [<code>ViewHelperApi</code>](#ViewHelperApi)  
**Summary**: Get the alert modal view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| dayDate | <code>string</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="COLLECTION_FORMATS"></a>

## COLLECTION\_FORMATS
**Kind**: global variable  
<a name="AlertDto"></a>

## AlertDto : <code>object</code>
**Kind**: global namespace  
<a name="AlertRefDto"></a>

## AlertRefDto : <code>object</code>
**Kind**: global namespace  
<a name="DayContext"></a>

## DayContext : <code>object</code>
**Kind**: global namespace  
<a name="DayTrend"></a>

## DayTrend : <code>object</code>
**Kind**: global namespace  
<a name="DayTrendInput"></a>

## DayTrendInput : <code>object</code>
**Kind**: global namespace  
<a name="AIApiFetchParamCreator"></a>

## AIApiFetchParamCreator()
AIApi - fetch parameter creator

**Kind**: global function  
<a name="v1AiAnomaliesSourceIdGet"></a>

## v1AiAnomaliesSourceIdGet(sourceId, [options])
**Kind**: global function  
**Summary**: Auto detect-anomalies  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeDayModelsSourceIdYearPost"></a>

## v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])
Erases and re-computes all day models for a source and year

**Kind**: global function  
**Summary**: Recomputes all day modesl  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeDaysProjectionSourceIdYearPost"></a>

## v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])
This computes the X/Y projection of all days in the source for the given year

**Kind**: global function  
**Summary**: Computes all days projection for a source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeModelsSourceIdYearPost"></a>

## v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])
This operations erases both non-handled alerts and user previsions

**Kind**: global function  
**Summary**: Triggers a model recompute  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [modelCount] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeSourceModelsModelCountPost"></a>

## v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])
This operations erases the group configuration

**Kind**: global function  
**Summary**: Triggers a model recompute for source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| modelCount | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AIApiFp"></a>

## AIApiFp()
AIApi - functional programming interface

**Kind**: global function  
<a name="v1AiAnomaliesSourceIdGet"></a>

## v1AiAnomaliesSourceIdGet(sourceId, [options])
**Kind**: global function  
**Summary**: Auto detect-anomalies  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeDayModelsSourceIdYearPost"></a>

## v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])
Erases and re-computes all day models for a source and year

**Kind**: global function  
**Summary**: Recomputes all day modesl  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeDaysProjectionSourceIdYearPost"></a>

## v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])
This computes the X/Y projection of all days in the source for the given year

**Kind**: global function  
**Summary**: Computes all days projection for a source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeModelsSourceIdYearPost"></a>

## v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])
This operations erases both non-handled alerts and user previsions

**Kind**: global function  
**Summary**: Triggers a model recompute  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [modelCount] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeSourceModelsModelCountPost"></a>

## v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])
This operations erases the group configuration

**Kind**: global function  
**Summary**: Triggers a model recompute for source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| modelCount | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AIApiFactory"></a>

## AIApiFactory()
AIApi - factory interface

**Kind**: global function  
<a name="v1AiAnomaliesSourceIdGet"></a>

## v1AiAnomaliesSourceIdGet(sourceId, [options])
**Kind**: global function  
**Summary**: Auto detect-anomalies  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeDayModelsSourceIdYearPost"></a>

## v1AiRecomputeDayModelsSourceIdYearPost(year, sourceId, [options])
Erases and re-computes all day models for a source and year

**Kind**: global function  
**Summary**: Recomputes all day modesl  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeDaysProjectionSourceIdYearPost"></a>

## v1AiRecomputeDaysProjectionSourceIdYearPost(year, sourceId, [options])
This computes the X/Y projection of all days in the source for the given year

**Kind**: global function  
**Summary**: Computes all days projection for a source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeModelsSourceIdYearPost"></a>

## v1AiRecomputeModelsSourceIdYearPost(year, sourceId, [modelCount], [options])
This operations erases both non-handled alerts and user previsions

**Kind**: global function  
**Summary**: Triggers a model recompute  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [modelCount] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AiRecomputeSourceModelsModelCountPost"></a>

## v1AiRecomputeSourceModelsModelCountPost(modelCount, [options])
This operations erases the group configuration

**Kind**: global function  
**Summary**: Triggers a model recompute for source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| modelCount | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AlertApiFetchParamCreator"></a>

## AlertApiFetchParamCreator()
AlertApi - fetch parameter creator

**Kind**: global function  
<a name="v1AlertAlertIdCommentPatch"></a>

## v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])
A commented alert is closed and is moved to the alert referential

**Kind**: global function  
**Summary**: Add a comment to an alert  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertCommentDto | <code>AlertCommentDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertAlertIdFavoritePatch"></a>

## v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])
**Kind**: global function  
**Summary**: Set alert favorite for the current user  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertFavoriteDto | <code>AlertFavoriteDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertListGet"></a>

## v1AlertListGet([sourceId], [year], [options])
**Kind**: global function  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertRefListGet"></a>

## v1AlertRefListGet([sourceId], [year], [options])
**Kind**: global function  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AlertApiFp"></a>

## AlertApiFp()
AlertApi - functional programming interface

**Kind**: global function  
<a name="v1AlertAlertIdCommentPatch"></a>

## v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])
A commented alert is closed and is moved to the alert referential

**Kind**: global function  
**Summary**: Add a comment to an alert  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertCommentDto | <code>AlertCommentDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertAlertIdFavoritePatch"></a>

## v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])
**Kind**: global function  
**Summary**: Set alert favorite for the current user  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertFavoriteDto | <code>AlertFavoriteDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertListGet"></a>

## v1AlertListGet([sourceId], [year], [options])
**Kind**: global function  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertRefListGet"></a>

## v1AlertRefListGet([sourceId], [year], [options])
**Kind**: global function  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="AlertApiFactory"></a>

## AlertApiFactory()
AlertApi - factory interface

**Kind**: global function  
<a name="v1AlertAlertIdCommentPatch"></a>

## v1AlertAlertIdCommentPatch(AlertCommentDto, alertId, [options])
A commented alert is closed and is moved to the alert referential

**Kind**: global function  
**Summary**: Add a comment to an alert  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertCommentDto | <code>AlertCommentDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertAlertIdFavoritePatch"></a>

## v1AlertAlertIdFavoritePatch(AlertFavoriteDto, alertId, [options])
**Kind**: global function  
**Summary**: Set alert favorite for the current user  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| AlertFavoriteDto | <code>AlertFavoriteDto</code> |  |
| alertId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertListGet"></a>

## v1AlertListGet([sourceId], [year], [options])
**Kind**: global function  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1AlertRefListGet"></a>

## v1AlertRefListGet([sourceId], [year], [options])
**Kind**: global function  
**Summary**: List alerts data of the selected year, all alerts if no year is provided  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [sourceId] | <code>number</code> |  |
| [year] | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayApiFetchParamCreator"></a>

## DayApiFetchParamCreator()
DayApi - fetch parameter creator

**Kind**: global function  
<a name="v1DayBulkPatch"></a>

## v1DayBulkPatch(DaysPatchDto, [options])
**Kind**: global function  
**Summary**: Update day entities  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DaysPatchDto | <code>DaysPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayListSourceIdYearGet"></a>

## v1DayListSourceIdYearGet(year, sourceId, [options])
**Kind**: global function  
**Summary**: List day data of the reference year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayApiFp"></a>

## DayApiFp()
DayApi - functional programming interface

**Kind**: global function  
<a name="v1DayBulkPatch"></a>

## v1DayBulkPatch(DaysPatchDto, [options])
**Kind**: global function  
**Summary**: Update day entities  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DaysPatchDto | <code>DaysPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayListSourceIdYearGet"></a>

## v1DayListSourceIdYearGet(year, sourceId, [options])
**Kind**: global function  
**Summary**: List day data of the reference year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayApiFactory"></a>

## DayApiFactory()
DayApi - factory interface

**Kind**: global function  
<a name="v1DayBulkPatch"></a>

## v1DayBulkPatch(DaysPatchDto, [options])
**Kind**: global function  
**Summary**: Update day entities  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DaysPatchDto | <code>DaysPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayListSourceIdYearGet"></a>

## v1DayListSourceIdYearGet(year, sourceId, [options])
**Kind**: global function  
**Summary**: List day data of the reference year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApiFetchParamCreator"></a>

## DayContextApiFetchParamCreator()
DayContextApi - fetch parameter creator

**Kind**: global function  
<a name="v1DayContextBulkPost"></a>

## v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])
**Kind**: global function  
**Summary**: Create many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayContextBulkDto | <code>GeneratedDayContextBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextGet"></a>

## v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdDelete"></a>

## v1DayContextIdDelete(id, [options])
**Kind**: global function  
**Summary**: Delete one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdGet"></a>

## v1DayContextIdGet(id, [fields], [join], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdPatch"></a>

## v1DayContextIdPatch(DayContext, id, [options])
**Kind**: global function  
**Summary**: Update one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdPut"></a>

## v1DayContextIdPut(DayContext, id, [options])
**Kind**: global function  
**Summary**: Replace one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextImportMeteoCsvSourceIdPost"></a>

## v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])
**Kind**: global function  
**Summary**: Imports a meteo csv file for the source id  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextPost"></a>

## v1DayContextPost(DayContext, [options])
**Kind**: global function  
**Summary**: Create one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApiFp"></a>

## DayContextApiFp()
DayContextApi - functional programming interface

**Kind**: global function  
<a name="v1DayContextBulkPost"></a>

## v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])
**Kind**: global function  
**Summary**: Create many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayContextBulkDto | <code>GeneratedDayContextBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextGet"></a>

## v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdDelete"></a>

## v1DayContextIdDelete(id, [options])
**Kind**: global function  
**Summary**: Delete one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdGet"></a>

## v1DayContextIdGet(id, [fields], [join], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdPatch"></a>

## v1DayContextIdPatch(DayContext, id, [options])
**Kind**: global function  
**Summary**: Update one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdPut"></a>

## v1DayContextIdPut(DayContext, id, [options])
**Kind**: global function  
**Summary**: Replace one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextImportMeteoCsvSourceIdPost"></a>

## v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])
**Kind**: global function  
**Summary**: Imports a meteo csv file for the source id  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextPost"></a>

## v1DayContextPost(DayContext, [options])
**Kind**: global function  
**Summary**: Create one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayContextApiFactory"></a>

## DayContextApiFactory()
DayContextApi - factory interface

**Kind**: global function  
<a name="v1DayContextBulkPost"></a>

## v1DayContextBulkPost(GeneratedDayContextBulkDto, [options])
**Kind**: global function  
**Summary**: Create many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayContextBulkDto | <code>GeneratedDayContextBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextGet"></a>

## v1DayContextGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve many DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdDelete"></a>

## v1DayContextIdDelete(id, [options])
**Kind**: global function  
**Summary**: Delete one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdGet"></a>

## v1DayContextIdGet(id, [fields], [join], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdPatch"></a>

## v1DayContextIdPatch(DayContext, id, [options])
**Kind**: global function  
**Summary**: Update one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextIdPut"></a>

## v1DayContextIdPut(DayContext, id, [options])
**Kind**: global function  
**Summary**: Replace one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextImportMeteoCsvSourceIdPost"></a>

## v1DayContextImportMeteoCsvSourceIdPost(sourceId, [options])
**Kind**: global function  
**Summary**: Imports a meteo csv file for the source id  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayContextPost"></a>

## v1DayContextPost(DayContext, [options])
**Kind**: global function  
**Summary**: Create one DayContext  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayContext | [<code>DayContext</code>](#DayContext) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApiFetchParamCreator"></a>

## DayTrendApiFetchParamCreator()
DayTrendApi - fetch parameter creator

**Kind**: global function  
<a name="v1DayTrendBulkPost"></a>

## v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])
**Kind**: global function  
**Summary**: Create many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayTrendBulkDto | <code>GeneratedDayTrendBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendGet"></a>

## v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdDelete"></a>

## v1DayTrendIdDelete(id, [options])
**Kind**: global function  
**Summary**: Delete one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdGet"></a>

## v1DayTrendIdGet(id, [fields], [join], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdPatch"></a>

## v1DayTrendIdPatch(DayTrend, id, [options])
**Kind**: global function  
**Summary**: Update one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdPut"></a>

## v1DayTrendIdPut(DayTrend, id, [options])
**Kind**: global function  
**Summary**: Replace one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendPost"></a>

## v1DayTrendPost(DayTrend, [options])
**Kind**: global function  
**Summary**: Create one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendReplaceAllInSourceSourceIdPost"></a>

## v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])
**Kind**: global function  
**Summary**: Imports many trends and replace existing. Recomputes alerts  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| DayTrendInputListDto | <code>DayTrendInputListDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApiFp"></a>

## DayTrendApiFp()
DayTrendApi - functional programming interface

**Kind**: global function  
<a name="v1DayTrendBulkPost"></a>

## v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])
**Kind**: global function  
**Summary**: Create many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayTrendBulkDto | <code>GeneratedDayTrendBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendGet"></a>

## v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdDelete"></a>

## v1DayTrendIdDelete(id, [options])
**Kind**: global function  
**Summary**: Delete one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdGet"></a>

## v1DayTrendIdGet(id, [fields], [join], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdPatch"></a>

## v1DayTrendIdPatch(DayTrend, id, [options])
**Kind**: global function  
**Summary**: Update one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdPut"></a>

## v1DayTrendIdPut(DayTrend, id, [options])
**Kind**: global function  
**Summary**: Replace one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendPost"></a>

## v1DayTrendPost(DayTrend, [options])
**Kind**: global function  
**Summary**: Create one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendReplaceAllInSourceSourceIdPost"></a>

## v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])
**Kind**: global function  
**Summary**: Imports many trends and replace existing. Recomputes alerts  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| DayTrendInputListDto | <code>DayTrendInputListDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="DayTrendApiFactory"></a>

## DayTrendApiFactory()
DayTrendApi - factory interface

**Kind**: global function  
<a name="v1DayTrendBulkPost"></a>

## v1DayTrendBulkPost(GeneratedDayTrendBulkDto, [options])
**Kind**: global function  
**Summary**: Create many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| GeneratedDayTrendBulkDto | <code>GeneratedDayTrendBulkDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendGet"></a>

## v1DayTrendGet([fields], [filter], [or], [sort], [join], [per_page], [offset], [page], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve many DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [filter] | <code>string</code> | &lt;h4&gt;Adds fields request condition (multiple conditions) to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?filter&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt; &lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;isVillain||eq||false&amp;filter&#x3D;city||eq||Arkham&lt;/strong&gt; (multiple filters are treated as a combination of AND type of conditions)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;shots||in||12,26&lt;/strong&gt; (some conditions accept multiple values separated by commas)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;power||isnull&lt;/strong&gt; (some conditions don&#39;t accept value)&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;Filter Conditions:&lt;ul&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;eq&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&#x3D;&lt;/code&gt;, equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ne&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;!&#x3D;&lt;/code&gt;, not equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&lt;/code&gt;, greater than)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lt&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&lt;/code&gt;, lower that)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;gte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;gt;&#x3D;&lt;/code&gt;, greater than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;lte&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;&amp;lt;&#x3D;&lt;/code&gt;, lower than or equal)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;starts&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE val%&lt;/code&gt;, starts with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;ends&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val&lt;/code&gt;, ends with)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;cont&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;LIKE %val%&lt;/code&gt;, contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;excl&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT LIKE %val%&lt;/code&gt;, not contains)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;in&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IN&lt;/code&gt;, in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notin&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;NOT IN&lt;/code&gt;, not in range, &lt;strong&gt;&lt;em&gt;accepts multiple values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;isnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NULL&lt;/code&gt;, is NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;notnull&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;IS NOT NULL&lt;/code&gt;, not NULL, &lt;strong&gt;&lt;em&gt;doesn&#39;t accept value&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;li&gt;&lt;strong&gt;&lt;code&gt;between&lt;/code&gt;&lt;/strong&gt; (&lt;code&gt;BETWEEN&lt;/code&gt;, between, &lt;strong&gt;&lt;em&gt;accepts two values&lt;/em&gt;&lt;/strong&gt;)&lt;/li&gt;&lt;/ul&gt; |
| [or] | <code>string</code> | &lt;h4&gt;Adds &lt;code&gt;OR&lt;/code&gt; conditions to the request.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?or&#x3D;field||condition||value&lt;/strong&gt;&lt;br/&gt;It uses the same conditions as the filter parameter&lt;br/&gt;&lt;i&gt;Rules and &lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;If there is only &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as simple filter:&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;multiple&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; present (without &lt;code&gt;filter&lt;/code&gt;) then it will be interpreted as a compination of &lt;code&gt;OR&lt;/code&gt; conditions, as follows:&lt;br&gt;&lt;code&gt;WHERE {or} OR {or} OR ...&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?or&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If there are &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;strong&gt;one&lt;/strong&gt; &lt;code&gt;filter&lt;/code&gt; then it will be interpreted as &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE {filter} OR {or}&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;name||eq||batman&amp;or&#x3D;name||eq||joker&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt;&lt;ul&gt;&lt;li&gt;If present &lt;strong&gt;both&lt;/strong&gt; &lt;code&gt;or&lt;/code&gt; and &lt;code&gt;filter&lt;/code&gt; in any amount (&lt;strong&gt;one&lt;/strong&gt; or &lt;strong&gt;miltiple&lt;/strong&gt; each) then both interpreted as a combitation of &lt;code&gt;AND&lt;/code&gt; conditions and compared with each other by &lt;code&gt;OR&lt;/code&gt; condition, as follows:&lt;br&gt;&lt;code&gt;WHERE ({filter} AND {filter} AND ...) OR ({or} AND {or} AND ...)&lt;/code&gt;&lt;/li&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?filter&#x3D;type||eq||hero&amp;filter&#x3D;status||eq||alive&amp;or&#x3D;type||eq||villain&amp;or&#x3D;status||eq||dead&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/ul&gt; |
| [sort] | <code>string</code> | &lt;h4&gt;Adds sort by field (by multiple fields) and order to query result.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?sort&#x3D;field,ASC|DESC&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?sort&#x3D;name,ASC&amp;sort&#x3D;id,DESC&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [per_page] | <code>number</code> | &lt;h4&gt;Receive &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?per_page&#x3D;10&lt;/strong&gt; |
| [offset] | <code>number</code> | &lt;h4&gt;Offset &lt;code&gt;N&lt;/code&gt; amount of entities.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?offset&#x3D;10&lt;/strong&gt; |
| [page] | <code>number</code> | &lt;h4&gt;Receive a portion of &lt;code&gt;limit&lt;/code&gt; entities (alternative to &lt;code&gt;offset&lt;/code&gt;). Will be applied if &lt;code&gt;limit&lt;/code&gt; is set up.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?page&#x3D;number&lt;/strong&gt;&lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?page&#x3D;2&lt;/strong&gt; |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdDelete"></a>

## v1DayTrendIdDelete(id, [options])
**Kind**: global function  
**Summary**: Delete one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdGet"></a>

## v1DayTrendIdGet(id, [fields], [join], [cache], [options])
**Kind**: global function  
**Summary**: Retrieve one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| id | <code>number</code> |  |
| [fields] | <code>string</code> | &lt;h4&gt;Selects fields that should be returned in the reponse body.&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;field1,field2,...&lt;/strong&gt; &lt;br/&gt;&lt;i&gt;Example:&lt;/i&gt; &lt;strong&gt;?fields&#x3D;email,name&lt;/strong&gt; |
| [join] | <code>string</code> | &lt;h4&gt;Receive joined relational objects in GET result (with all or selected fields).&lt;/h4&gt;&lt;i&gt;Syntax:&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation||field1,field2,...&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1||field11,field12,...&amp;join&#x3D;relation1.nested||field21,field22,...&amp;join&#x3D;...&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;br/&gt;&lt;i&gt;Examples:&lt;/i&gt;&lt;/i&gt;&lt;ul&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;profile||firstName,email&amp;join&#x3D;notifications||content&amp;join&#x3D;tasks&lt;/strong&gt;&lt;/li&gt;&lt;li&gt;&lt;strong&gt;?join&#x3D;relation1&amp;join&#x3D;relation1.nested&amp;join&#x3D;relation1.nested.deepnested&lt;/strong&gt;&lt;/li&gt;&lt;/ul&gt;&lt;strong&gt;&lt;i&gt;Notice:&lt;/i&gt;&lt;/strong&gt; &lt;code&gt;id&lt;/code&gt; field always persists in relational objects. To use nested relations, the parent level MUST be set before the child level like example above. |
| [cache] | <code>number</code> | &lt;h4&gt;Reset cache (if was enabled) and receive entities from the DB.&lt;/h4&gt;&lt;i&gt;Usage:&lt;/i&gt; &lt;strong&gt;?cache&#x3D;0&lt;/strong&gt; |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdPatch"></a>

## v1DayTrendIdPatch(DayTrend, id, [options])
**Kind**: global function  
**Summary**: Update one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendIdPut"></a>

## v1DayTrendIdPut(DayTrend, id, [options])
**Kind**: global function  
**Summary**: Replace one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| id | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendPost"></a>

## v1DayTrendPost(DayTrend, [options])
**Kind**: global function  
**Summary**: Create one DayTrend  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| DayTrend | [<code>DayTrend</code>](#DayTrend) |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1DayTrendReplaceAllInSourceSourceIdPost"></a>

## v1DayTrendReplaceAllInSourceSourceIdPost(sourceId, DayTrendInputListDto, [options])
**Kind**: global function  
**Summary**: Imports many trends and replace existing. Recomputes alerts  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| DayTrendInputListDto | <code>DayTrendInputListDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ImportApiFetchParamCreator"></a>

## ImportApiFetchParamCreator()
ImportApi - fetch parameter creator

**Kind**: global function  
<a name="v1ImportCreateSourcePost"></a>

## v1ImportCreateSourcePost(CreateSourceDto, [options])
Creates a source, add a first batch of day data, then computes the models for the first time.

**Kind**: global function  
**Summary**: First source creation  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| CreateSourceDto | <code>CreateSourceDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportDaysPost"></a>

## v1ImportDaysPost(ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: global function  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportReprocessDaysSourceIdYearPost"></a>

## v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])
Compute maps, alerts and closest models

**Kind**: global function  
**Summary**: Reprocess days from database  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportSourceIdDaysPost"></a>

## v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: global function  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ImportApiFp"></a>

## ImportApiFp()
ImportApi - functional programming interface

**Kind**: global function  
<a name="v1ImportCreateSourcePost"></a>

## v1ImportCreateSourcePost(CreateSourceDto, [options])
Creates a source, add a first batch of day data, then computes the models for the first time.

**Kind**: global function  
**Summary**: First source creation  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| CreateSourceDto | <code>CreateSourceDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportDaysPost"></a>

## v1ImportDaysPost(ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: global function  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportReprocessDaysSourceIdYearPost"></a>

## v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])
Compute maps, alerts and closest models

**Kind**: global function  
**Summary**: Reprocess days from database  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportSourceIdDaysPost"></a>

## v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: global function  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ImportApiFactory"></a>

## ImportApiFactory()
ImportApi - factory interface

**Kind**: global function  
<a name="v1ImportCreateSourcePost"></a>

## v1ImportCreateSourcePost(CreateSourceDto, [options])
Creates a source, add a first batch of day data, then computes the models for the first time.

**Kind**: global function  
**Summary**: First source creation  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| CreateSourceDto | <code>CreateSourceDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportDaysPost"></a>

## v1ImportDaysPost(ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: global function  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportReprocessDaysSourceIdYearPost"></a>

## v1ImportReprocessDaysSourceIdYearPost(year, sourceId, [options])
Compute maps, alerts and closest models

**Kind**: global function  
**Summary**: Reprocess days from database  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ImportSourceIdDaysPost"></a>

## v1ImportSourceIdDaysPost(sourceId, ImportDaysDto, [options])
When new data is added, we compute alerts for this data

**Kind**: global function  
**Summary**: Add new data to a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| ImportDaysDto | <code>ImportDaysDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ModelApiFetchParamCreator"></a>

## ModelApiFetchParamCreator()
ModelApi - fetch parameter creator

**Kind**: global function  
<a name="v1ModelBulkPatch"></a>

## v1ModelBulkPatch(ModelsPatchDto, [options])
Update many models at once, mainly used to set color and name of the model

**Kind**: global function  
**Summary**: Model bulk update  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ModelsPatchDto | <code>ModelsPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ModelListSourceIdGet"></a>

## v1ModelListSourceIdGet(sourceId, [options])
**Kind**: global function  
**Summary**: List models data of this source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ModelApiFp"></a>

## ModelApiFp()
ModelApi - functional programming interface

**Kind**: global function  
<a name="v1ModelBulkPatch"></a>

## v1ModelBulkPatch(ModelsPatchDto, [options])
Update many models at once, mainly used to set color and name of the model

**Kind**: global function  
**Summary**: Model bulk update  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ModelsPatchDto | <code>ModelsPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ModelListSourceIdGet"></a>

## v1ModelListSourceIdGet(sourceId, [options])
**Kind**: global function  
**Summary**: List models data of this source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ModelApiFactory"></a>

## ModelApiFactory()
ModelApi - factory interface

**Kind**: global function  
<a name="v1ModelBulkPatch"></a>

## v1ModelBulkPatch(ModelsPatchDto, [options])
Update many models at once, mainly used to set color and name of the model

**Kind**: global function  
**Summary**: Model bulk update  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| ModelsPatchDto | <code>ModelsPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ModelListSourceIdGet"></a>

## v1ModelListSourceIdGet(sourceId, [options])
**Kind**: global function  
**Summary**: List models data of this source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApiFetchParamCreator"></a>

## PrevisionApiFetchParamCreator()
PrevisionApi - fetch parameter creator

**Kind**: global function  
<a name="v1PrevisionGroupApplyPrevisionPost"></a>

## v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])
**Kind**: global function  
**Summary**: Apply a source prevision to the whole group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionApplyGroupDto | <code>PrevisionApplyGroupDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionListSourceIdYearGet"></a>

## v1PrevisionListSourceIdYearGet(year, sourceId, [options])
**Kind**: global function  
**Summary**: Fetch data previsions for a given year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionSaveDefaultPrevisionsSourceIdYearPost"></a>

## v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])
**Kind**: global function  
**Summary**: Generate default previsions for the source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionSavePost"></a>

## v1PrevisionSavePost(PrevisionBulkSaveDto, [options])
**Kind**: global function  
**Summary**: Save many previsions at once  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionBulkSaveDto | <code>PrevisionBulkSaveDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionUpdatePatch"></a>

## v1PrevisionUpdatePatch(PrevisionPatchDto, [options])
**Kind**: global function  
**Summary**: Update a specific prevision  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionPatchDto | <code>PrevisionPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApiFp"></a>

## PrevisionApiFp()
PrevisionApi - functional programming interface

**Kind**: global function  
<a name="v1PrevisionGroupApplyPrevisionPost"></a>

## v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])
**Kind**: global function  
**Summary**: Apply a source prevision to the whole group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionApplyGroupDto | <code>PrevisionApplyGroupDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionListSourceIdYearGet"></a>

## v1PrevisionListSourceIdYearGet(year, sourceId, [options])
**Kind**: global function  
**Summary**: Fetch data previsions for a given year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionSaveDefaultPrevisionsSourceIdYearPost"></a>

## v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])
**Kind**: global function  
**Summary**: Generate default previsions for the source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionSavePost"></a>

## v1PrevisionSavePost(PrevisionBulkSaveDto, [options])
**Kind**: global function  
**Summary**: Save many previsions at once  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionBulkSaveDto | <code>PrevisionBulkSaveDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionUpdatePatch"></a>

## v1PrevisionUpdatePatch(PrevisionPatchDto, [options])
**Kind**: global function  
**Summary**: Update a specific prevision  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionPatchDto | <code>PrevisionPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="PrevisionApiFactory"></a>

## PrevisionApiFactory()
PrevisionApi - factory interface

**Kind**: global function  
<a name="v1PrevisionGroupApplyPrevisionPost"></a>

## v1PrevisionGroupApplyPrevisionPost(PrevisionApplyGroupDto, [options])
**Kind**: global function  
**Summary**: Apply a source prevision to the whole group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionApplyGroupDto | <code>PrevisionApplyGroupDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionListSourceIdYearGet"></a>

## v1PrevisionListSourceIdYearGet(year, sourceId, [options])
**Kind**: global function  
**Summary**: Fetch data previsions for a given year  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionSaveDefaultPrevisionsSourceIdYearPost"></a>

## v1PrevisionSaveDefaultPrevisionsSourceIdYearPost(year, sourceId, [options])
**Kind**: global function  
**Summary**: Generate default previsions for the source and save them  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| year | <code>number</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionSavePost"></a>

## v1PrevisionSavePost(PrevisionBulkSaveDto, [options])
**Kind**: global function  
**Summary**: Save many previsions at once  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionBulkSaveDto | <code>PrevisionBulkSaveDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1PrevisionUpdatePatch"></a>

## v1PrevisionUpdatePatch(PrevisionPatchDto, [options])
**Kind**: global function  
**Summary**: Update a specific prevision  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| PrevisionPatchDto | <code>PrevisionPatchDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceApiFetchParamCreator"></a>

## SourceApiFetchParamCreator()
SourceApi - fetch parameter creator

**Kind**: global function  
<a name="v1SourceListGet"></a>

## v1SourceListGet([options])
**Kind**: global function  
**Summary**: All user sources  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdDelete"></a>

## v1SourceSourceIdDelete(sourceId, [options])
**Kind**: global function  
**Summary**: Delete a source and all linked data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdGroupPatch"></a>

## v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])
**Kind**: global function  
**Summary**: Update a source group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchGroupDto | <code>SourcePatchGroupDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdPatch"></a>

## v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])
**Kind**: global function  
**Summary**: Update a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchDto | <code>SourcePatchDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceApiFp"></a>

## SourceApiFp()
SourceApi - functional programming interface

**Kind**: global function  
<a name="v1SourceListGet"></a>

## v1SourceListGet([options])
**Kind**: global function  
**Summary**: All user sources  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdDelete"></a>

## v1SourceSourceIdDelete(sourceId, [options])
**Kind**: global function  
**Summary**: Delete a source and all linked data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdGroupPatch"></a>

## v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])
**Kind**: global function  
**Summary**: Update a source group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchGroupDto | <code>SourcePatchGroupDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdPatch"></a>

## v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])
**Kind**: global function  
**Summary**: Update a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchDto | <code>SourcePatchDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceApiFactory"></a>

## SourceApiFactory()
SourceApi - factory interface

**Kind**: global function  
<a name="v1SourceListGet"></a>

## v1SourceListGet([options])
**Kind**: global function  
**Summary**: All user sources  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdDelete"></a>

## v1SourceSourceIdDelete(sourceId, [options])
**Kind**: global function  
**Summary**: Delete a source and all linked data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdGroupPatch"></a>

## v1SourceSourceIdGroupPatch(SourcePatchGroupDto, sourceId, [options])
**Kind**: global function  
**Summary**: Update a source group  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchGroupDto | <code>SourcePatchGroupDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceSourceIdPatch"></a>

## v1SourceSourceIdPatch(SourcePatchDto, sourceId, [options])
**Kind**: global function  
**Summary**: Update a source  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourcePatchDto | <code>SourcePatchDto</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceGroupApiFetchParamCreator"></a>

## SourceGroupApiFetchParamCreator()
SourceGroupApi - fetch parameter creator

**Kind**: global function  
<a name="v1SourceGroupCreatePost"></a>

## v1SourceGroupCreatePost(SourceGroupCreateDto, [options])
**Kind**: global function  
**Summary**: Create a new source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupCreateDto | <code>SourceGroupCreateDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceGroupGroupIdPatch"></a>

## v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])
**Kind**: global function  
**Summary**: Updates a group configuration  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupPatchDto | <code>SourceGroupPatchDto</code> |  |
| groupId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceGroupListGet"></a>

## v1SourceGroupListGet([options])
**Kind**: global function  
**Summary**: All source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceGroupApiFp"></a>

## SourceGroupApiFp()
SourceGroupApi - functional programming interface

**Kind**: global function  
<a name="v1SourceGroupCreatePost"></a>

## v1SourceGroupCreatePost(SourceGroupCreateDto, [options])
**Kind**: global function  
**Summary**: Create a new source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupCreateDto | <code>SourceGroupCreateDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceGroupGroupIdPatch"></a>

## v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])
**Kind**: global function  
**Summary**: Updates a group configuration  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupPatchDto | <code>SourceGroupPatchDto</code> |  |
| groupId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceGroupListGet"></a>

## v1SourceGroupListGet([options])
**Kind**: global function  
**Summary**: All source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="SourceGroupApiFactory"></a>

## SourceGroupApiFactory()
SourceGroupApi - factory interface

**Kind**: global function  
<a name="v1SourceGroupCreatePost"></a>

## v1SourceGroupCreatePost(SourceGroupCreateDto, [options])
**Kind**: global function  
**Summary**: Create a new source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupCreateDto | <code>SourceGroupCreateDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceGroupGroupIdPatch"></a>

## v1SourceGroupGroupIdPatch(SourceGroupPatchDto, groupId, [options])
**Kind**: global function  
**Summary**: Updates a group configuration  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| SourceGroupPatchDto | <code>SourceGroupPatchDto</code> |  |
| groupId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1SourceGroupListGet"></a>

## v1SourceGroupListGet([options])
**Kind**: global function  
**Summary**: All source groups  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="UserApiFetchParamCreator"></a>

## UserApiFetchParamCreator()
UserApi - fetch parameter creator

**Kind**: global function  
<a name="v1UserLoginPost"></a>

## v1UserLoginPost(LoginDto, [options])
This endpoints returns the jwt and sets a cookie with the same jwt.      This way you can use it from both an api and a browser

**Kind**: global function  
**Summary**: Log the user in  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| LoginDto | <code>LoginDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1UserMeGet"></a>

## v1UserMeGet([options])
Must be authenticated to call this endpoint

**Kind**: global function  
**Summary**: Retrieve current user information  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1UserRegisterDemoPost"></a>

## v1UserRegisterDemoPost(RequestDemoDto, [options])
**Kind**: global function  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| RequestDemoDto | <code>RequestDemoDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="UserApiFp"></a>

## UserApiFp()
UserApi - functional programming interface

**Kind**: global function  
<a name="v1UserLoginPost"></a>

## v1UserLoginPost(LoginDto, [options])
This endpoints returns the jwt and sets a cookie with the same jwt.      This way you can use it from both an api and a browser

**Kind**: global function  
**Summary**: Log the user in  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| LoginDto | <code>LoginDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1UserMeGet"></a>

## v1UserMeGet([options])
Must be authenticated to call this endpoint

**Kind**: global function  
**Summary**: Retrieve current user information  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1UserRegisterDemoPost"></a>

## v1UserRegisterDemoPost(RequestDemoDto, [options])
**Kind**: global function  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| RequestDemoDto | <code>RequestDemoDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="UserApiFactory"></a>

## UserApiFactory()
UserApi - factory interface

**Kind**: global function  
<a name="v1UserLoginPost"></a>

## v1UserLoginPost(LoginDto, [options])
This endpoints returns the jwt and sets a cookie with the same jwt.      This way you can use it from both an api and a browser

**Kind**: global function  
**Summary**: Log the user in  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| LoginDto | <code>LoginDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1UserMeGet"></a>

## v1UserMeGet([options])
Must be authenticated to call this endpoint

**Kind**: global function  
**Summary**: Retrieve current user information  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1UserRegisterDemoPost"></a>

## v1UserRegisterDemoPost(RequestDemoDto, [options])
**Kind**: global function  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| RequestDemoDto | <code>RequestDemoDto</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ViewHelperApiFetchParamCreator"></a>

## ViewHelperApiFetchParamCreator()
ViewHelperApi - fetch parameter creator

**Kind**: global function  
<a name="v1ViewHelperAlertsGet"></a>

## v1ViewHelperAlertsGet([options])
**Kind**: global function  
**Summary**: Get the alert view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ViewHelperAlertsRefGet"></a>

## v1ViewHelperAlertsRefGet([options])
**Kind**: global function  
**Summary**: Get the alert referential view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ViewHelperDaysNearDateSourceIdDayDateGet"></a>

## v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])
**Kind**: global function  
**Summary**: Get the alert modal view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| dayDate | <code>string</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ViewHelperApiFp"></a>

## ViewHelperApiFp()
ViewHelperApi - functional programming interface

**Kind**: global function  
<a name="v1ViewHelperAlertsGet"></a>

## v1ViewHelperAlertsGet([options])
**Kind**: global function  
**Summary**: Get the alert view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ViewHelperAlertsRefGet"></a>

## v1ViewHelperAlertsRefGet([options])
**Kind**: global function  
**Summary**: Get the alert referential view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ViewHelperDaysNearDateSourceIdDayDateGet"></a>

## v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])
**Kind**: global function  
**Summary**: Get the alert modal view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| dayDate | <code>string</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

<a name="ViewHelperApiFactory"></a>

## ViewHelperApiFactory()
ViewHelperApi - factory interface

**Kind**: global function  
<a name="v1ViewHelperAlertsGet"></a>

## v1ViewHelperAlertsGet([options])
**Kind**: global function  
**Summary**: Get the alert view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ViewHelperAlertsRefGet"></a>

## v1ViewHelperAlertsRefGet([options])
**Kind**: global function  
**Summary**: Get the alert referential view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>\*</code> | Override http request option. |

<a name="v1ViewHelperDaysNearDateSourceIdDayDateGet"></a>

## v1ViewHelperDaysNearDateSourceIdDayDateGet(dayDate, sourceId, [options])
**Kind**: global function  
**Summary**: Get the alert modal view data  
**Throws**:

- [<code>RequiredError</code>](#RequiredError) 


| Param | Type | Description |
| --- | --- | --- |
| dayDate | <code>string</code> |  |
| sourceId | <code>number</code> |  |
| [options] | <code>\*</code> | Override http request option. |

