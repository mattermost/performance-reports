### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 2ms | 14ms | 12ms | 793.84
| UserStore.GetAllProfiles | avg | 3ms | 7ms | 4ms | 134.20
| ChannelStore.CreateSidebarCategory | avg | 29ms | 45ms | 16ms | 54.63
| ChannelStore.GetMembersForUserWithPagination | avg | 28ms | 32ms | 4ms | 14.53
| ChannelStore.AnalyticsTypeCount | avg | 63ms | 70ms | 7ms | 11.14
| PostStore.SearchPostsForUser | avg | 116ms | 125ms | 9ms | 7.78
| UserStore.GetAllProfilesInChannel | avg | 262ms | 278ms | 16ms | 6.10
| ChannelStore.Autocomplete | avg | 42ms | 44ms | 2ms | 4.81
| TeamStore.SaveMember | avg | 64ms | 66ms | 2ms | 3.11
| UserStore.AutocompleteUsersInChannel | avg | 125ms | 128ms | 3ms | 2.40
| UserStore.AnalyticsActiveCount | avg | 141ms | 144ms | 3ms | 2.13
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 5ms | 231ms | 226ms | 4565.66
| UserStore.GetAllProfiles | p99 | 17ms | 193ms | 176ms | 1065.47
| BotStore.Get | p99 | 5ms | 22ms | 17ms | 343.43
| ChannelStore.Autocomplete | p99 | 100ms | 176ms | 76ms | 76.25
| PostStore.SearchPostsForUser | p99 | 1.473s | 2.41s | 937ms | 63.62
| PluginStore.List | p99 | 5ms | 8ms | 3ms | 60.61
| UserStore.GetProfilesInChannel | p99 | 5ms | 8ms | 3ms | 60.11
| ThreadStore.GetTotalUnreadMentions | p99 | 11ms | 16ms | 5ms | 46.92
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.488s | 3.588s | 1.1s | 44.21
| StatusStore.Get | p99 | 7ms | 10ms | 3ms | 40.25
| ChannelStore.SearchGroupChannels | p99 | 5ms | 7ms | 2ms | 40.09
| TeamStore.SaveMember | p99 | 100ms | 138ms | 38ms | 38.04
| ChannelStore.GetMembersForUser | p99 | 6ms | 8ms | 2ms | 34.82
| ProductNoticesStore.View | p99 | 99ms | 133ms | 34ms | 34.50
| ThreadStore.GetTeamsUnreadForUser | p99 | 14ms | 18ms | 4ms | 29.50
| TeamStore.GetTeamsForUser | p99 | 12ms | 15ms | 3ms | 25.92
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 8ms | 10ms | 2ms | 25.29
| ChannelStore.CreateInitialSidebarCategories | p99 | 50ms | 62ms | 12ms | 24.00
| UserStore.GetForLogin | p99 | 14ms | 17ms | 3ms | 21.24
| TeamStore.GetAllPage | p99 | 9ms | 11ms | 2ms | 21.13
| TeamStore.GetTeamsByUserId | p99 | 10ms | 12ms | 2ms | 20.33
| UserStore.AutocompleteUsersInChannel | p99 | 313ms | 366ms | 53ms | 16.95
| FileInfoStore.Save | p99 | 12ms | 14ms | 2ms | 16.24
| SessionStore.Get | p99 | 25ms | 28ms | 3ms | 11.97
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 25ms | 28ms | 3ms | 11.97
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 17ms | 19ms | 2ms | 11.48
| ChannelStore.SaveMember | p99 | 82ms | 86ms | 4ms | 4.87
| UserStore.GetAllProfilesInChannel | p99 | 893ms | 926ms | 33ms | 3.69
| UserStore.Save | p99 | 158ms | 163ms | 5ms | 3.16
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.Update | avg | 8ms | 0s | -8ms | -100.87
| ChannelStore.GetTeamChannels | avg | 24ms | 0s | -24ms | -100.78
| SchemeStore.GetAllPage | avg | 5ms | 1ms | -4ms | -88.42
| FileInfoStore.Search | avg | 21ms | 10ms | -11ms | -52.87
| ChannelStore.UpdateSidebarCategories | avg | 87ms | 49ms | -38ms | -43.84
| ChannelStore.Save | avg | 10ms | 8ms | -2ms | -20.05
| UserStore.Count | avg | 40ms | 32ms | -8ms | -19.92
| StatusStore.SaveOrUpdate | avg | 21ms | 17ms | -4ms | -19.27
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetTeamChannels | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.Update | p99 | 10ms | 0s | -10ms | -100.50
| JobStore.GetCountByStatusAndType | p99 | 55ms | 5ms | -50ms | -90.91
| FileInfoStore.Search | p99 | 49ms | 10ms | -39ms | -79.19
| JobStore.UpdateOptimistically | p99 | 37ms | 9ms | -28ms | -76.19
| ChannelStore.Save | p99 | 87ms | 22ms | -65ms | -75.14
| ChannelStore.GetMembersForUserWithPagination | p99 | 193ms | 50ms | -143ms | -74.11
| PostStore.Delete | p99 | 25ms | 10ms | -15ms | -60.98
| ChannelStore.GetSidebarCategory | p99 | 21ms | 9ms | -12ms | -56.07
| UserStore.GetByUsername | p99 | 10ms | 5ms | -5ms | -52.63
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 5ms | -5ms | -51.46
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.51
| PostAcknowledgementStore.GetForPost | p99 | 16ms | 9ms | -7ms | -44.81
| UserStore.Count | p99 | 175ms | 98ms | -77ms | -44.01
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -43.96
| JobStore.GetNewestJobByStatusesAndType | p99 | 8ms | 5ms | -3ms | -37.27
| ThreadStore.GetThreadFollowers | p99 | 7ms | 5ms | -2ms | -28.86
| FileInfoStore.AttachToPost | p99 | 18ms | 13ms | -5ms | -27.87
| StatusStore.SaveOrUpdate | p99 | 407ms | 304ms | -103ms | -25.32
| PluginStore.Delete | p99 | 12ms | 10ms | -2ms | -17.30
| ThreadStore.GetThreadForUser | p99 | 14ms | 12ms | -2ms | -14.63
| ChannelStore.GetChannelsByUser | p99 | 86ms | 76ms | -10ms | -11.63
| UserStore.GetUnreadCount | p99 | 659ms | 583ms | -76ms | -11.54
| FileInfoStore.SetContent | p99 | 23ms | 21ms | -2ms | -8.58
| PreferenceStore.Save | p99 | 36ms | 33ms | -3ms | -8.40
| ChannelStore.UpdateSidebarCategories | p99 | 246ms | 239ms | -7ms | -2.84
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsers | avg | 4ms | 8ms | 4ms | 94.89
| getLicenseSelfServeStatus | avg | 43ms | 74ms | 31ms | 71.65
| createCategoryForTeamForUser | avg | 39ms | 63ms | 24ms | 61.39
| getChannelsForUser | avg | 25ms | 37ms | 12ms | 47.06
| getFilteredUsersStats | avg | 16ms | 23ms | 7ms | 44.12
| getChannelMembersForUser | avg | 24ms | 34ms | 10ms | 42.47
| setPostReminder | avg | 11ms | 13ms | 2ms | 18.80
| logout | avg | 32ms | 38ms | 6ms | 18.74
| searchPostsInTeam | avg | 120ms | 133ms | 13ms | 10.85
| handleCheckCWSConnection | avg | 38ms | 42ms | 4ms | 10.65
| removeUserCustomStatus | avg | 123ms | 136ms | 13ms | 10.59
| autocompleteUsers | avg | 92ms | 97ms | 5ms | 5.43
| addTeamMember | avg | 785ms | 826ms | 41ms | 5.22
| searchAllChannels | avg | 42ms | 44ms | 2ms | 4.79
| createGroupChannel | avg | 267ms | 277ms | 10ms | 3.74
| updateUserCustomStatus | avg | 151ms | 154ms | 3ms | 1.99
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsers | p99 | 22ms | 206ms | 184ms | 819.01
| upsertDraft | p99 | 5ms | 10ms | 5ms | 100.78
| getFilteredUsersStats | p99 | 49ms | 94ms | 45ms | 91.03
| setPostReminder | p99 | 25ms | 47ms | 22ms | 89.25
| searchAllChannels | p99 | 100ms | 176ms | 76ms | 76.23
| updateUserCustomStatus | p99 | 248ms | 436ms | 188ms | 75.72
| searchPostsInTeam | p99 | 1.473s | 2.41s | 937ms | 63.62
| searchGroupChannels | p99 | 5ms | 8ms | 3ms | 60.14
| removeUserCustomStatus | p99 | 248ms | 388ms | 140ms | 56.50
| autocompleteChannelsForTeamForSearch | p99 | 2.488s | 3.588s | 1.1s | 44.21
| getChannel | p99 | 5ms | 7ms | 2ms | 40.04
| uploadFileStream | p99 | 998ms | 1.271s | 273ms | 27.35
| getChannelMembersForTeamForUser | p99 | 7ms | 9ms | 2ms | 26.92
| autocompleteUsers | p99 | 250ms | 310ms | 60ms | 24.02
| getTeamMembersForUser | p99 | 17ms | 21ms | 4ms | 23.23
| getTeamsForUser | p99 | 10ms | 12ms | 2ms | 20.32
| getChannelsForTeamForUser | p99 | 10ms | 12ms | 2ms | 20.12
| getPostThread | p99 | 18ms | 21ms | 3ms | 16.82
| getCategoriesForTeamForUser | p99 | 27ms | 30ms | 3ms | 11.20
| getTeamsUnreadForUser | p99 | 19ms | 21ms | 2ms | 10.63
| getChannelMember | p99 | 32ms | 35ms | 3ms | 9.46
| getLicenseSelfServeStatus | p99 | 234ms | 246ms | 12ms | 5.12
| addChannelMember | p99 | 468ms | 480ms | 12ms | 2.57
| getPostsForChannelAroundLastUnread | p99 | 827ms | 848ms | 21ms | 2.54
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelByNameForTeamName | avg | 2ms | 0s | -2ms | -118.06
| patchUser | avg | 65ms | 0s | -65ms | -100.41
| createChannel | avg | 24ms | 0s | -24ms | -100.31
| updateConfig | avg | 176ms | 0s | -176ms | -100.06
| updateCategoryForTeamForUser | avg | 198ms | 0s | -198ms | -99.96
| updateViewedProductNotices | avg | 8ms | 0s | -8ms | -94.51
| searchFiles | avg | 22ms | 10ms | -12ms | -54.91
| patchPost | avg | 453ms | 212ms | -241ms | -53.23
| deletePost | avg | 13ms | 11ms | -2ms | -15.38
| updateCategoriesForTeamForUser | avg | 66ms | 56ms | -10ms | -15.21
| getProfileImage | avg | 107ms | 100ms | -7ms | -6.52
| createDirectChannel | avg | 206ms | 199ms | -7ms | -3.40
| getAnalytics | avg | 88ms | 86ms | -2ms | -2.28
| addChannelMember | avg | 195ms | 192ms | -3ms | -1.54
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelByNameForTeamName | p99 | 5ms | 0s | -5ms | -101.01
| createChannel | p99 | 25ms | 0s | -25ms | -100.60
| patchUser | p99 | 100ms | 0s | -100ms | -100.50
| updateViewedProductNotices | p99 | 10ms | 0s | -10ms | -100.50
| getSelfHostedProducts | p99 | 5ms | 0s | -5ms | -100.37
| updateCategoryForTeamForUser | p99 | 249ms | 0s | -249ms | -100.20
| updateConfig | p99 | 249ms | 0s | -249ms | -100.20
| searchFiles | p99 | 99ms | 25ms | -74ms | -75.13
| logout | p99 | 97ms | 50ms | -47ms | -48.70
| updateCategoriesForTeamForUser | p99 | 460ms | 239ms | -221ms | -48.04
| getAnalytics | p99 | 458ms | 247ms | -211ms | -46.05
| unfollowThreadByUser | p99 | 17ms | 10ms | -7ms | -40.35
| createPost | p99 | 1.692s | 1.243s | -449ms | -26.54
| updatePreferences | p99 | 20ms | 18ms | -2ms | -10.17
| updateReadStateThreadByUser | p99 | 38ms | 36ms | -2ms | -5.27
| saveReaction | p99 | 38ms | 36ms | -2ms | -5.22
| getFilePreview | p99 | 210ms | 204ms | -6ms | -2.86
| getProfileImage | p99 | 489ms | 479ms | -10ms | -2.04
| getChannelsForUser | p99 | 735ms | 720ms | -15ms | -2.04
| createDirectChannel | p99 | 491ms | 486ms | -5ms | -1.02
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 22ms | 17ms | 343.434
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 4ms | 1ms | 28.711
| |  P99| 17ms| 19ms | 2ms | 11.476
| ChannelStore.AnalyticsTypeCount |  Avg| 63ms| 70ms | 7ms | 11.137
| |  P99| 99ms| 100ms | 1ms | 1.005
| ChannelStore.Autocomplete |  Avg| 42ms| 44ms | 2ms | 4.815
| |  P99| 100ms| 176ms | 76ms | 76.251
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 353ms| 355ms | 2ms | 0.567
| |  P99| 2.488s| 3.588s | 1.1s | 44.211
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 13ms| 14ms | 1ms | 7.417
| |  P99| 50ms| 62ms | 12ms | 24.002
| ChannelStore.CreateSidebarCategory |  Avg| 29ms| 45ms | 16ms | 54.633
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 87ms| 87ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.057
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 0s | -1ms | -123.560
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 86ms| 76ms | -10ms | -11.628
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 6.011
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 243ms| 245ms | 2ms | 0.822
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 76ms| 76ms | 0s | 0.000
| |  P99| 247ms| 246ms | -1ms | -0.406
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 34.819
| ChannelStore.GetMembersForUserWithPagination |  Avg| 28ms| 32ms | 4ms | 14.528
| |  P99| 193ms| 50ms | -143ms | -74.112
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.029
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.003
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 11.965
| ChannelStore.GetSidebarCategory |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -56.074
| ChannelStore.GetTeamChannels |  Avg| 24ms| 0s | -24ms | -100.784
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 8ms | -2ms | -20.051
| |  P99| 87ms| 22ms | -65ms | -75.143
| ChannelStore.SaveMember |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 82ms| 86ms | 4ms | 4.865
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.095
| ChannelStore.Update |  Avg| 8ms| 0s | -8ms | -100.874
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.323
| ChannelStore.UpdateSidebarCategories |  Avg| 87ms| 49ms | -38ms | -43.844
| |  P99| 246ms| 239ms | -7ms | -2.842
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 2ms| 14ms | 12ms | 793.842
| |  P99| 5ms| 231ms | 226ms | 4565.657
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 3ms | -1ms | -27.167
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 13ms | -5ms | -27.872
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 5ms | 1ms | 22.441
| |  P99| 12ms| 14ms | 2ms | 16.236
| FileInfoStore.Search |  Avg| 21ms| 10ms | -11ms | -52.872
| |  P99| 49ms| 10ms | -39ms | -79.188
| FileInfoStore.SetContent |  Avg| 8ms| 7ms | -1ms | -12.961
| |  P99| 23ms| 21ms | -2ms | -8.582
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.286
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.964
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.599
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 1ms | -1ms | -45.362
| |  P99| 55ms| 5ms | -50ms | -90.909
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.267
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 9ms | -28ms | -76.190
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.331
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.072
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 3ms | -1ms | -27.398
| |  P99| 10ms| 9ms | -1ms | -10.446
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.301
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.532
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -44.807
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| PostPersistentNotificationStore.Get |  Avg| 1ms| 2ms | 1ms | 71.826
| |  P99| 21ms| 21ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.666
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 2.109s| 2.101s | -8ms | -0.379
| |  P99| 4.951s| 4.952s | 1ms | 0.020
| PostStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 10ms | -15ms | -60.976
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.234
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 8ms| 9ms | 1ms | 11.860
| |  P99| 90ms| 90ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.855
| PostStore.SearchPostsForUser |  Avg| 116ms| 125ms | 9ms | 7.782
| |  P99| 1.473s| 2.41s | 937ms | 63.616
| PostStore.SetPostReminder |  Avg| 5ms| 6ms | 1ms | 18.277
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 3.960
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 36ms| 33ms | -3ms | -8.404
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 99ms| 133ms | 34ms | 34.504
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ReactionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 5ms| 1ms | -4ms | -88.418
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 11.969
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.508
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 40.248
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 21ms| 17ms | -4ms | -19.270
| |  P99| 407ms| 304ms | -103ms | -25.320
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 3ms | -1ms | -24.803
| |  P99| 10ms| 5ms | -5ms | -51.458
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.673
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.134
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.031
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.334
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 25.925
| TeamStore.SaveMember |  Avg| 64ms| 66ms | 2ms | 3.110
| |  P99| 100ms| 138ms | 38ms | 38.038
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 18ms | 4ms | 29.501
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.862
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.635
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.221
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 16ms | 5ms | 46.919
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.105
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.878
| ThreadStore.MaintainMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.725
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.956
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 141ms| 144ms | 3ms | 2.127
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 125ms| 128ms | 3ms | 2.404
| |  P99| 313ms| 366ms | 53ms | 16.952
| UserStore.Count |  Avg| 40ms| 32ms | -8ms | -19.921
| |  P99| 175ms| 98ms | -77ms | -44.006
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 7ms | 4ms | 134.200
| |  P99| 17ms| 193ms | 176ms | 1065.472
| UserStore.GetAllProfilesInChannel |  Avg| 262ms| 278ms | 16ms | 6.100
| |  P99| 893ms| 926ms | 33ms | 3.695
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.627
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 21.239
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.112
| UserStore.GetUnreadCount |  Avg| 14ms| 15ms | 1ms | 7.093
| |  P99| 659ms| 583ms | -76ms | -11.540
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.106
| UserStore.Save |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 158ms| 163ms | 5ms | 3.161
| UserStore.Search |  Avg| 25ms| 26ms | 1ms | 3.923
| |  P99| 241ms| 242ms | 1ms | 0.414
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.944
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.103
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.595
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 195ms| 192ms | -3ms | -1.537
| | P99| 468ms| 480ms | 12ms | 2.565
| addTeamMember | Avg| 785ms| 826ms | 41ms | 5.222
| | P99| 2.4s| 2.418s | 18ms | 0.750
| autocompleteChannelsForTeamForSearch | Avg| 353ms| 355ms | 2ms | 0.567
| | P99| 2.488s| 3.588s | 1.1s | 44.211
| autocompleteEmojis | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| autocompleteUsers | Avg| 92ms| 97ms | 5ms | 5.428
| | P99| 250ms| 310ms | 60ms | 24.022
| createCategoryForTeamForUser | Avg| 39ms| 63ms | 24ms | 61.393
| | P99| 99ms| 100ms | 1ms | 1.010
| createChannel | Avg| 24ms| 0s | -24ms | -100.312
| | P99| 25ms| 0s | -25ms | -100.604
| createDirectChannel | Avg| 206ms| 199ms | -7ms | -3.401
| | P99| 491ms| 486ms | -5ms | -1.018
| createGroupChannel | Avg| 267ms| 277ms | 10ms | 3.743
| | P99| 496ms| 497ms | 1ms | 0.202
| createPost | Avg| 275ms| 276ms | 1ms | 0.364
| | P99| 1.692s| 1.243s | -449ms | -26.544
| createUser | Avg| 89ms| 90ms | 1ms | 1.121
| | P99| 239ms| 241ms | 2ms | 0.836
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 13ms| 11ms | -2ms | -15.382
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 6ms| 7ms | 1ms | 15.482
| | P99| 10ms| 10ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 14ms| 15ms | 1ms | 7.191
| getAnalytics | Avg| 88ms| 86ms | -2ms | -2.278
| | P99| 458ms| 247ms | -211ms | -46.048
| getCategoriesForTeamForUser | Avg| 4ms| 5ms | 1ms | 22.409
| | P99| 27ms| 30ms | 3ms | 11.203
| getChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.043
| getChannelByNameForTeamName | Avg| 2ms| 0s | -2ms | -118.065
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 32ms| 35ms | 3ms | 9.465
| getChannelMembersForTeamForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 7ms| 9ms | 2ms | 26.920
| getChannelMembersForUser | Avg| 24ms| 34ms | 10ms | 42.468
| | P99| 50ms| 50ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 184ms| 183ms | -1ms | -0.542
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 12ms | 2ms | 20.117
| getChannelsForUser | Avg| 25ms| 37ms | 12ms | 47.064
| | P99| 735ms| 720ms | -15ms | -2.041
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 210ms| 204ms | -6ms | -2.857
| getFileThumbnail | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 97ms| 96ms | -1ms | -1.032
| getFilteredUsersStats | Avg| 16ms| 23ms | 7ms | 44.118
| | P99| 49ms| 94ms | 45ms | 91.029
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getLicenseSelfServeStatus | Avg| 43ms| 74ms | 31ms | 71.651
| | P99| 234ms| 246ms | 12ms | 5.124
| getPostThread | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 18ms| 21ms | 3ms | 16.823
| getPostsForChannel | Avg| 14ms| 13ms | -1ms | -7.362
| | P99| 99ms| 98ms | -1ms | -1.014
| getPostsForChannelAroundLastUnread | Avg| 36ms| 37ms | 1ms | 2.792
| | P99| 827ms| 848ms | 21ms | 2.538
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 20ms | -1ms | -4.821
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 107ms| 100ms | -7ms | -6.521
| | P99| 489ms| 479ms | -10ms | -2.044
| getPublicChannelsForTeam | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.001
| getRolesByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getSelfHostedProducts | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -100.366
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 21ms | 4ms | 23.228
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 10ms| 12ms | 2ms | 20.319
| getTeamsUnreadForUser | Avg| 2ms| 3ms | 1ms | 41.785
| | P99| 19ms| 21ms | 2ms | 10.626
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUser | Avg| 1ms| 2ms | 1ms | 71.112
| | P99| 18ms| 19ms | 1ms | 5.693
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 8ms | 4ms | 94.892
| | P99| 22ms| 206ms | 184ms | 819.011
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 38ms| 42ms | 4ms | 10.649
| | P99| 50ms| 50ms | 0s | 0.000
| login | Avg| 57ms| 57ms | 0s | 0.000
| | P99| 245ms| 246ms | 1ms | 0.408
| logout | Avg| 32ms| 38ms | 6ms | 18.742
| | P99| 97ms| 50ms | -47ms | -48.704
| patchPost | Avg| 453ms| 212ms | -241ms | -53.227
| | P99| 10s| 10s | 0s | 0.000
| patchUser | Avg| 65ms| 0s | -65ms | -100.411
| | P99| 100ms| 0s | -100ms | -100.503
| removeUserCustomStatus | Avg| 123ms| 136ms | 13ms | 10.590
| | P99| 248ms| 388ms | 140ms | 56.503
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 38ms| 36ms | -2ms | -5.223
| searchAllChannels | Avg| 42ms| 44ms | 2ms | 4.788
| | P99| 100ms| 176ms | 76ms | 76.233
| searchFiles | Avg| 22ms| 10ms | -12ms | -54.907
| | P99| 99ms| 25ms | -74ms | -75.127
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.142
| searchPostsInTeam | Avg| 120ms| 133ms | 13ms | 10.850
| | P99| 1.473s| 2.41s | 937ms | 63.616
| searchUsers | Avg| 26ms| 27ms | 1ms | 3.811
| | P99| 242ms| 243ms | 1ms | 0.413
| setPostReminder | Avg| 11ms| 13ms | 2ms | 18.803
| | P99| 25ms| 47ms | 22ms | 89.249
| unfollowThreadByUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 17ms| 10ms | -7ms | -40.351
| updateCategoriesForTeamForUser | Avg| 66ms| 56ms | -10ms | -15.206
| | P99| 460ms| 239ms | -221ms | -48.045
| updateCategoryForTeamForUser | Avg| 198ms| 0s | -198ms | -99.956
| | P99| 249ms| 0s | -249ms | -100.201
| updateConfig | Avg| 176ms| 0s | -176ms | -100.060
| | P99| 249ms| 0s | -249ms | -100.201
| updatePreferences | Avg| 7ms| 6ms | -1ms | -15.383
| | P99| 20ms| 18ms | -2ms | -10.168
| updateReadStateThreadByUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 38ms| 36ms | -2ms | -5.266
| updateUserCustomStatus | Avg| 151ms| 154ms | 3ms | 1.989
| | P99| 248ms| 436ms | 188ms | 75.716
| updateViewedProductNotices | Avg| 8ms| 0s | -8ms | -94.508
| | P99| 10ms| 0s | -10ms | -100.503
| uploadFileStream | Avg| 447ms| 449ms | 2ms | 0.447
| | P99| 998ms| 1.271s | 273ms | 27.354
| upsertDraft | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 5ms| 10ms | 5ms | 100.776
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.083
